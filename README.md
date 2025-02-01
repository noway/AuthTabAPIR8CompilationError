# Auth Tab API R8 compilation error

## Repro steps

- `git clone git@github.com:noway/AuthTabAPIR8CompilationError.git`
- `npm install`
- Open `android` folder in Android Studio
- Sync Gradle
- Run 'app'

You will see `Cannot invoke "String.length()" because "<parameter1>" is null` R8 compilation error coming from `androidx/browser/auth/AuthTabIntent$AuthenticateUserResultContract.class`
