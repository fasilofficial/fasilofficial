<h1 align='center'>Hey <img src="https://fonts.gstatic.com/s/e/notoemoji/latest/1f44b/512.gif" alt="👋" width="32" height="32">, I'm Fasil </h1>
<h4 align="center">DEVELOPER. PHOTOGRAPHER. CINEPHILE.</h4>

```php



use Illuminate\Support\Facades\Route;

Route::get('/about', fn() => response()->json([
    'fullName' => 'Muhammed Fasil K',
    'interests' => ['coding', 'movies', 'music', 'travel'],
    'skills' => ['ReactJS', 'Node.js', 'Laravel', 'Python', 'MySQL'],
]));

Route::get('/contact', fn() => response()->json([
    'email' => 'muhammedfasilofficial@gmail.com',
    'portfolio' => 'https://mfasil.vercel.app',
]));

Route::fallback(fn() => response()->json(['message' => 'Route not found'], 404));




```
