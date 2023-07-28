# Tabela carros sql

CREATE TABLE carro (
    id INT AUTO_INCREMENT PRIMARY KEY,
    marca VARCHAR(50) NOT NULL,
    modelo VARCHAR(50) NOT NULL,
    ano INT NOT NULL,
    cor VARCHAR(20),
    placa VARCHAR(10) UNIQUE,
    quilometragem FLOAT,
    preco DECIMAL(10, 2),
    data_compra DATE
);
