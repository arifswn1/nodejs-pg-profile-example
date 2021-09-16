# nodejs-pg-profile-example
ini adalah sample node js menggunakan database postgresql

## create database postgresql
* CREATE DATABASE db_profile;
* CREATE TABLE tb_user (
	id serial NOT NULL,
	nama varchar(50) NOT NULL,
	alamat varchar(100) NOT NULL,
	no_telp varchar(15) NOT NULL,
	CONSTRAINT tb_user_pk PRIMARY KEY (id)
);
* INSERT INTO tb_user (nama,alamat,no_telp) VALUES
	 ('Diah','Kedaton','-'),
	 ('Linda','Kedamaian','-');


let`s enjoy life !