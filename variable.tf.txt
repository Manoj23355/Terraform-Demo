variable "aws_region" {
  type = string
  default = "us-east-1"
}

variable "instance_type" {
  type = string
  default = "t2.micro"
}

variable "ami_id" {
  type = string
  default = "ami-0261755bbcb8c4a84"
}

variable "cidr" {
  type = string
   default = "10.0.0.0/16"
}

variable "allowed_ports" {
 type = list(number) 
 default = [22, 80, 443]
}
