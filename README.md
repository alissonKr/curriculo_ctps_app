# curriculo_ctps_app

Aplicativo mobile desenvolvido em Flutter que gera currículos automaticamente a partir de prints da Carteira de Trabalho Digital (CTPS).  
A proposta é simples: 100% gratuito, funcional offline, e sem dependência de APIs pagas.

---

## Funcionalidades

- Upload de imagem da CTPS digital
- OCR offline com ML Kit (Google)
- Extração de dados como Empresa, Cargo, Datas
- Geração automática de um modelo de currículo simples
- (em breve) Exportação em PDF e compartilhamento

---

## Tecnologias usadas

- Flutter + Dart
- Google ML Kit (Text Recognition)
- Regex / parsing manual em Dart
- Geração de PDF (pacote `pdf` do Dart)

---

## Como rodar localmente

```bash
git clone https://github.com/alissonKr/curriculo_ctps_app.git
cd curriculo_ctps_app
flutter pub get
flutter run
```

