# WeatherApp

 WeatherApp

WeatherApp to prosta aplikacja pogodowa, która umożliwia użytkownikom sprawdzenie aktualnej pogody oraz prognozy na najbliższe godziny i dni.

## Funkcje

- Wyświetlanie aktualnej pogody dla danej lokalizacji
- Możliwość wyszukiwania pogody dla określonego miasta
- Prognoza pogody na najbliższe godziny i dni
- Łatwe przeglądanie pogody za pomocą interfejsu ViewPager2 i zakładek
-Otrzymywanie powiadomień pogodowych

## Technologie

- Kotlin - język programowania
- Android Jetpack - biblioteka do tworzenia aplikacji Android
- Volley - biblioteka do obsługi żądań sieciowych
- Picasso - biblioteka do ładowania obrazów z internetu
- Google Location Services - usługa do zarządzania lokalizacją użytkownika

## Zależności

dependencies {
    // Jetpack
    implementation libs.androidx.core.ktx
    implementation libs.androidx.appcompat
    implementation libs.androidx.fragmentKtx
    implementation libs.androidx.constraintlayout
    implementation libs.material
    implementation libs.androidx.activity
    implementation libs.androidx.tools.core

    // Volley
    implementation "com.android.volley:volley:1.2.1"

    // Picasso
    implementation "com.squareup.picasso:picasso:2.8"

    // Google Location Services
    implementation "com.google.android.gms:play-services-location:21.2.0"

## Uprawnienia

<uses-permission android:name="android.permission.INTERNET"/>
<uses-permission android:name="android.permission.ACCESS_COARSE_LOCATION"/>
<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>
<uses-permission android:name="android.permission.POST_NOTIFICATIONS" />
Te uprawnienia są niezbędne dla Twojej aplikacji, aby mogła korzystać z Internetu, uzyskiwać dostęp do lokalizacji oraz wysyłać powiadomienia. 

## Wykorzystanie
Uruchom aplikację na swoim urządzeniu Android.
Jeśli pojawia się pytanie o udostępnienie lokalizacji, zezwól na to, aby aplikacja mogła wyświetlić aktualną pogodę dla Twojej lokalizacji.
Aby sprawdzić pogodę dla innego miasta, kliknij ikonę lupy, wprowadź nazwę miasta i naciśnij przycisk "OK".
Przewiń w prawo lub lewo, aby przejść między zakładkami "Godziny" i "Dni", aby zobaczyć prognozę pogody na najbliższe godziny lub dni.


Arsen Nedohybchenko nr albumu 40950
