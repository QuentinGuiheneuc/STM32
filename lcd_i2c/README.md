# LCD I2C 2*16 a 4*20

### Les fonctions

- le premier arument c'est I2C, deuxieme le max de colone du lcd, le troixieme le max de ligne du lcd.

```
lcd_i2c_init(I2C_HandleTypeDef *pI2cHandle,uint8_t colone,uint8_t ligne)
```

- le poit de debut charrater row 0 - 4 , col 0 - 20

```
lcd_i2c_setCursor(row,col)
```

- Affiche les donne en charrater

```
lcd_i2c_printf(char)
```
