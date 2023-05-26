# otokocikinciel.com Web Scrap Uygulaması

https://img.shields.io/badge/tested%20with-Playwright-blue

## 📚 İçerik
- [Kurulum](#-Kurulum)
- [Kullanım](#-Kullanım)
- [Özet](#-Özet)
- [Installation](#-Installation)
- [Usage](#-Usage)
- [Summary](#-Summary)

Bu uygulama, Otokoc İkinci El Araba web sitesindeki araç verilerini toplayan ve bu verileri JSON ve XLSX formatlarında kaydeden bir otomasyon testidir. Uygulama, Playwright ve XLSX kütüphanelerini kullanarak oluşturulmuştur.

## Kurulum

Proje bağımlılıklarını kurmak için aşağıdaki adımları izleyin:

1.`npm install playwright xlsx`
2. `tests` klasörünün içerisine dosyaları kopyalayın.

## Kullanım

Uygulamayı çalıştırmak için aşağıdaki adımları izleyin:

1. `otokoc.spec.js` dosyasındaki testin çalışması için aşağıdaki komutu çalıştırın:
Bu test, Otokoc web sitesindeki araç verilerini toplayacak ve `output.json` dosyasına kaydedecektir.
2. `araclar.test.js` dosyasındaki testin çalışması için aşağıdaki komutu çalıştırın:
Bu test, `output.json` dosyasındaki araç URL'lerini ziyaret ederek araç detaylarını ve satıcı bilgilerini toplayacak. Ardından, `ikinci.json` ve `veri.xlsx` dosyalarını oluşturacaktır.
3. İlgili dosyaların oluşturulduğunu ve verilerin kaydedildiğini görebileceksiniz.

## Özet

1. `otokoc.spec.js` dosyası, Otokoc İkinci El Araba web sitesindeki araç verilerini toplar ve `output.json` dosyasına kaydeder.
2. `araclar.test.js` dosyası, `output.json` dosyasındaki araç URL'lerini ziyaret ederek araç detaylarını ve satıcı bilgilerini toplar. Sonuçları `ikinci.json` ve `veri.xlsx` dosyalarına kaydeder.
3. Uygulamayı kullanabilmek için gerekli adımlar `Kurulum` bölümünde açıklanmıştır.
4. Uygulamayı çalıştırmak için `Kullanım` bölümündeki talimatları izleyin.

---

# Otokocikinciel.com Web Scraping Application

This application is an automation test that collects vehicle data from the Otokoc Second Hand Car website and saves this data in JSON and XLSX formats. The application is built using Playwright and XLSX libraries.

## Installation

Follow the steps below to install project dependencies:

1. Run `npm install playwright xlsx`.
2. Copy the files into the `tests` folder.

## Usage

Follow the steps below to run the application:

1. Run the following command to execute the test in the `otokoc.spec.js` file:
   This test will collect vehicle data from the Otokoc website and save it to the `output.json` file.

2. Run the following command to execute the test in the `araclar.test.js` file:
   This test will visit the vehicle URLs in the `output.json` file, collect vehicle details and seller information, and then generate the `ikinci.json` and `veri.xlsx` files.

3. You can see that the relevant files are generated and the data is saved.

## Summary

1. The `otokoc.spec.js` file collects vehicle data from the Otokoc Second Hand Car website and saves it to the `output.json` file.

2. The `araclar.test.js` file visits the vehicle URLs in the `output.json` file, collects vehicle details and seller information, and saves the results to the `ikinci.json` and `veri.xlsx` files.

3. Follow the steps in the `Installation` section to set up and use the application.

4. Follow the instructions in the `Usage` section to run the application.

---



