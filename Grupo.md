Um **grupo** no Linux é uma coleção de **usuários** que compartilha um conjunto comum de permissões de acesso a arquivos e outros recursos do sistema.

- **Grupo Primário (ou Principal):** É o grupo padrão associado a um usuário quando ele é criado. Todo arquivo que o usuário cria tem o seu grupo primário como grupo proprietário (a menos que seja especificado o contrário).

- **Grupos Secundários (ou Suplementares):** São grupos adicionais aos quais um usuário pertence. Estes dão ao usuário as permissões de acesso a recursos específicos que esses grupos controlam.

sudo usermod -aG teste paulo2