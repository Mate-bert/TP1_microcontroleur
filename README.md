# Compte rendu TP microcontroleur

## Le GPIO Expander et le VU-Metre
### Configuration

1) La référence du GPIO expandeur est MCP23S17.

2) Sur le STM32 le SPI3 est utilisé.

3) Nous modifions les paramètres du SPI3 pour que la largeur de la data soit fixé sur 8 bits et nous configurons les PIN du stm32 en rapport avec ce que nous avons dans la datasheet.

## LE Codec AUDIO SGTL5000
### Configuration préaliables

1) On utilise le I2C3 de la carte et celui-ci utilise les PINs "PB10" pour la ligne de la clock (SCL) et "PB11" pour la ligne de la data (SDA).

### Configuration codec par I2C

Nous observons bien la valeur du registre sur l'oscilloscope, celui-ci forme un 0x14 en bianire. 

### Signaux I2S

Nous avons reussi a observer les différents signaux de clocks. 

### Génération de signal audio

Nous n'avons malheurement pas reussi a générer un signal triangulaire.




 
