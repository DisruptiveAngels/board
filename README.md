# README

> Plataforma de contenido curado para toda la comunidad de Noches de Pitcheo

## Creat new user

Create new user

```rb
u = User.new
```

Assign user email

```rb
u.email = 'user-email'
```

Assign user password

```rb
u.password = 'user-password'
```

Assign user role

```rb
#Default role: 0
#Admin role: 1
u.role = 0
```

Save user

```rb
u.save
```