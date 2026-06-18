# Ansible Playbook Builder

> Generador visual de playbooks d'Ansible.

Selecciona mòduls, configura paràmetres i genera playbooks YAML d'Ansible de manera visual, sense escriure codi manualment.

## Tecnologies

- HTML + CSS + JavaScript (vanilla)
- [Tailwind CSS](https://tailwindcss.com/) (via CDN)
- [Font Awesome](https://fontawesome.com/) (icons)
- [Fira Code](https://github.com/tonsky/FiraCode) + [Inter](https://rsms.me/inter/) fonts

## Mòduls disponibles

apt, copy, template, service, user, file, lineinfile, shell, git, docker_container

## Funcionalitats

- Més de 10 mòduls Ansible predefinits
- Configuració visual de paràmetres per mòdul
- Suport de variables, hosts i become
- Generació YAML formatada automàticament
- Edició i eliminació de tasques
- Exportació de playbook.yml
- Copiar al portapapers

## Ús

Obre `ansible-playbook-builder.html` al navegador, configura els paràmetres globals del playbook, selecciona mòduls i configura'ls, i descarrega el playbook generat.
