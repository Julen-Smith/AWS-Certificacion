#
# Sources 
#   https://docs.aws.amazon.com/cli/latest/reference/ec2/describe-regions.html
#   https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-regions-availability-zones.html#concepts-availability-zones
#
#
#

# Comandos utiles regiones
#
#   Listar todas las regiones : aws ec2 describe-regions --all-regions --query "Regions[].{Name:RegionName}" --output text
#   Zonas de disponibilidad regiones  aws ec2 describe-availability-zones --region region-name
#
#
#
