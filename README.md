# flutter-fvm-setup-action
GitHub action for setting up Flutter using [FVM](https://fvm.app/). The Flutter version is determined by the project's .fvmrc file.

## Involved steps
1. Setting up FVM
2. Installing Flutter
3. Running `flutter pub get`

## Usage
Add the following step to your GitHub Actions workflow:

```yaml
- name: 🐦 Setup Flutter
  uses: antigua-mobile/flutter-fvm-setup-action@v1.0
```