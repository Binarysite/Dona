# Doná

Doná es una aplicación que tiene como principal objetivo hacer más ameno el hecho de donar dinero del saldo a instituciones sin fines de lucro asociadas con Antel.

Doná utiliza el servicio de donaciones a través de mensajes de texto de Antel para realizar las donaciones, por lo que no funciona con otras operadoras.


#Set up

1. Install node packages
```
npm install
npm install --only=dev
```

2. Modify the src directory, this is where your application will live

3. Install Android Studio

4. Add the platforms you desire
```
tns platform add ios
tns platform add android
```

5. Build with Gulp
```
gulp
```

6. Emulate or deploy!
```
tns emulate ios
```

# License

MIT License

Copyright (c) 2017 Binary

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
