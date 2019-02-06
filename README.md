# Aplikacja "Uczniowie"
Aplikacja sieciowa pozwalająca na dodawanie uczniów do klas.

## Widoki

1. Strona główna: z wyjaśnieniem przeznaczenia aplikacji.
2. Dodaj klasę: widok umożliwiający dodawanie klas.
3. Edytuj klasę: widok umożliwiający edycję danych klasy.
4. Dodaj ucznia: widok umożliwiający dodawanie ucznia.
5. Dodaj ucznia: widok umożliwiający edycję danych ucznia.
6. Lista klas: wyświetla klasy i ich dane.
7. Lista uczniów: wyświetla uczniów i ich dane.

## Wygląd

1. Szablon oparty na Bootstrapie.

## Narzędzia

1. Python 3
2. Flask
3. flask-wtf
4. Peewee

Ewentualne przygotowanie wirtualnego środowiska:

```python
python3 -m venv pve
source pve/bin/activate
```

Instalacja bibliotek:

```python
pip install flask flask-wtf peewee
```

Uruchomienie serwera deweloperskiego:

```python
python app.py
```

<ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="{{url_for('dodaj_kl')}}">Dodaj klasę</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="{{url_for('edytuj_kl')}}">Edytuj klasę</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="{{url_for('lista_kl')}}">Lista klas</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="{{url_for('dodaj_ucz')}}">Dodaj ucznia</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="{{url_for('edytuj_ucz')}}">Edytuj ucznia</a>
            </li>
            <li class="nav-item">
              <a class="nav-link js-scroll-trigger" href="{{url_for('lista_ucz')}}">Lista uczniow</a>
            </li>
</ul>
