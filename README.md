# Emre Mert Dübüş - Assignment 3


# Android Navigasyon Örneği

Bu depo, fragmentler arası geçiş yapmak için Navigation component'inin kullanımını gösteren basit bir Android uygulamasını içerir.

## Genel Bakış

Uygulamada üç ana fragment bulunmaktadır:
- `AccountFragment`: Kullanıcıların yeni bir hesap oluşturmak için `CreateAccountFragment`e veya giriş yapmak için `LoginAccountFragment`e geçiş yapabileceği başlangıç fragmenti.
- `CreateAccountFragment`: Kullanıcıların yeni bir hesap oluşturabileceği fragment.
- `LoginAccountFragment`: Kullanıcıların hesaplarına giriş yapabileceği fragment. Başarılı bir giriş, kullanıcıyı `ProfileFragment`e yönlendirir.
- `ProfileFragment`: Kullanıcıların başarılı bir giriş sonrası gördüğü ve kullanıcı profilinin gösterildiği fragment.

## Navigasyon Grafiği

Uygulamanın navigasyon akışı, tek bir `NavHostFragment` içinde Navigation component tarafından yönetilir. Navigasyon grafiği (`nav_account.xml`), yukarıda bahsedilen fragmentler arasındaki ilişkileri tanımlar.

## Başlarken

Bu projeye başlamak için, bu depoyu klonlayın .

```bash
git clone https://github.com/Getir-Android-Kotlin-Bootcamp/getir-android-kotlin-bootcamp-w3-assignment-EmreMertD.git
```

Projeyi klonladıktan sonra, bir Android emülatöründe veya gerçek bir cihazda derleyip çalıştırabilirsiniz.

## Bağımlılıklar

Proje aşağıdaki bağımlılıkları kullanır:
- `androidx.navigation:navigation-fragment-ktx`
- `androidx.navigation:navigation-ui-ktx`


[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/USlt-hrg)
# w3-assignment
Getir Android Kotlin Bootcamp w3 Assignment

## Onboarding navigation akışını iki farklı akış biçimine getireceğiz. 
Onboarding nav kalacak

Account nav oluşturacak

