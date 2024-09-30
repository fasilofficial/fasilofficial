<h1 align='center'>Hey <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f44b/512.gif" alt="👋" width="32" height="32">, I'm Fasil </h1>
<h4 align="center">DEVELOPER. PHOTOGRAPHER. CINEPHILE.</h4>

```php



<?php

use Illuminate\Support\Facades\Route;
use Symfony\Component\HttpFoundation\Response;


Route::get('/about', function () {
    return response()->json([
        'fullName' => 'Muhammed Fasil K',
        'interests' => ['coding', 'movies', 'music', 'travel'],
        'askMeAbout' => ['web development', 'movies'],
        'skills' => [
            'ReactJS',
            'NextJS',
            'Node.js',
            'Express.js',
            'NestJS',
            'Laravel',
            'Python',
            'MongoDB',
            'MySQL',
        ],
    ], Response::HTTP_OK);
});

Route::get('/contact', function () {
    return response()->json([
        'email' => 'muhammedfasilofficial@gmail.com',
        'portfolio' => 'https://mfasil.vercel.app',
        'links' => [
            'linkedin' => 'https://www.linkedin.com/in/mfasilofficial',
            'leetcode' => 'https://leetcode.com/fasilofficial',
        ],
    ], Response::HTTP_OK);
});

Route::fallback(function () {
    return response()->json(['message' => 'Route not found'], Response::HTTP_NOT_FOUND);
});



```
