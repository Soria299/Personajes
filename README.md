Tema: Personajes

Script de la BD
-- Crear la base de datos
CREATE DATABASE DBPersonajes;
GO

-- Usar la base de datos creada
USE DBPersonajes;
GO

-- Crear la tabla Personajes
CREATE TABLE Personajes (
    Id INT IDENTITY(1,1) PRIMARY KEY,
    Nombre NVARCHAR(100) NOT NULL,
    Nivel INT NOT NULL,
    Tipo NVARCHAR(50) NOT NULL
);

INSERT INTO Personajes (Nombre, Nivel, Tipo) VALUES 
('Sol', 70, 'Paladín'),
('Luna', 25, 'Invocadora'),
('Drako', 50, 'Bestia'),
('Kira', 90, 'Sacerdotisa'),
('Ragnar', 35, 'Gladiador');

