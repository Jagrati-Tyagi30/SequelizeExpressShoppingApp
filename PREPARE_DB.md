 #Preparing the database

 '''sql
 CREATE DATABASE Database1;
 create user shopper identified by 'shoppass';
 use shopdb;
 grant all privileges on Database1 to shopper;
 grant all privileges on Database1.* to shopper;
 '''