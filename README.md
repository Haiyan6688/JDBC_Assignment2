# JDBC_Assignment2

SQL kod:

CREATE TABLE `sqlandjava`.`cars` (
  `cars_id` INT NOT NULL,
  `brand` VARCHAR(45) NOT NULL,
  `color` VARCHAR(45) NOT NULL,
  PRIMARY KEY (`cars_id`));

INSERT INTO `sqlandjava`.`cars` (`cars_id`, `brand`, `color`) VALUES ('1', 'Volvo', 'Black');
INSERT INTO `sqlandjava`.`cars` (`cars_id`, `brand`, `color`) VALUES ('2', 'Saab', 'Blue');
INSERT INTO `sqlandjava`.`cars` (`cars_id`, `brand`, `color`) VALUES ('3', 'Audi', 'Red');
INSERT INTO `sqlandjava`.`cars` (`cars_id`, `brand`, `color`) VALUES ('4', 'Ford', 'Green');

GRANT SELECT ON sqlandjava.cars TO super@localhost;
