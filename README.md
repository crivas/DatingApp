#UDEMY Course

##Create first migrations
dotnet ef migrations Add InitialCreate -o Data/Migrations 

##Create database from model 
dotnet ef database update

##run
dotnet watch run