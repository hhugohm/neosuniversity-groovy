# Spring Boot 2.x

Repositorio que tiene el ejemplo de un proyecto con Spring Boot 2.x y manejo de groovy.

----------------------------------
Pasos para instalación de proyecto :neosuniversity-groovy
----------------------------------
1.- Crear una carpeta neosuniversity-groovy (omitir este paso si se cloana el repositorio)

2.- Ejecutar  (omitir este paso si se cloana el repositorio)
```ruby
vi app.groovy
```
```ruby
@RestController
class ThisWillActuallyRun {

	@RequestMapping("/")
		String home() {
				"Hola Mundo Spring Boot 2.x"
		}
	}
```
3.- Ejecutar
```ruby
$ spring run app.groovy
```
```ruby
$ curl localhost:8080/
Hola Mundo Sprng Boot 2.x
```
