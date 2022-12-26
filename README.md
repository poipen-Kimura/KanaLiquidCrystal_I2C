# KanaLiquidCrystal_I2C

LiquidCrystal Arduino library for I2C LCD displays

This is an attempt to implement the half-width kana display function of [synapse.kyoto's KanaLiquidCrystal library](https://synapse.kyoto/lib/KanaLiquidCrystal/page001.html) into [johnrickman's LiquidCrystal_I2C library](https://github.com/johnrickman/LiquidCrystal_I2C).

## simple usage

```ino
KanaLiquidCrystal_I2C lcd(0x27,16,2);

  lcd.init();
  lcd.kanaOn(); //-- switch of hankaku-kana enable
  
  lcd.print("ｺﾆ-ﾁﾊ- ｾｶ-ｲ");

```