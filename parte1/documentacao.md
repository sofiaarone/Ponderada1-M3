## Parte 1 - Blink LED Interno

### Código no Arduino

```
void setup() {
  pinMode(LED_BUILTIN, OUTPUT); // define o LED interno como saída
}

void loop() {
  digitalWrite(LED_BUILTIN, HIGH); // acende o LED
  delay(1000);                     // espera 1 segundo
  digitalWrite(LED_BUILTIN, LOW);  // apaga o LED
  delay(500);                      // espera 0,5 segundos
}
```

### Vídeo de demonstração: 

[Assista ao vídeo](https://drive.google.com/file/d/1VLH-ztHz1ISW-2T_EpvnMqk9XI0DDVBm/view?t=9)