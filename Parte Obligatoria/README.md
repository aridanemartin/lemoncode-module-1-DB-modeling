# lemoncode-module-1-DB-modeling

Top Videos - Aplico el subset pattern en el que sobreescribiré en el front-end los vídeos que me interese mostrar en la página principal y no me supondrá un coste elevado ya que la subida no será tan frecuente.

Course_detail - Genero una colección usando el patrón "Extended Ref" mediante la copia del campo "name" e "id" de los autores del curso.

Course - Se relaciona mediante el patrón "Extended Ref" usando solo los campos extrictamente necesarios de las colecciones "Video", "Category" y "Author".

Author - Se relaciona por "Extended Ref" con Course para traer los cursos de un determinado autor.
