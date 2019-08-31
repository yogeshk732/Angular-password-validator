# Angular password field validation for formGroup

<ul>
<li>Add password.strength.ts file into your project.</li>
<li>Import file into component.ts</li>
<li>Use into FormGroup <br>

  ```form = new FormGroup({
    email: new FormControl('', [
      Validators.required,
      Validators.email
    ]),
    password: new FormControl('', [Validators.required, PasswordStrengthValidator]),
  });```
</li>
</ul>
