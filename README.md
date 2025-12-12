## 👨‍💻 Fullstack Developer

```python
class Desenvolvedor:
    def __init__(self):
        self.nome = "Seu Nome"
        self.idade = 23
        self.localizacao = "Brasil 🇧🇷"
        self.role = "Fullstack Developer"
        
    def stack_atual(self):
        return {
            "frontend": ["React", "Next.js", "TailwindCSS"],
            "backend": ["Python", "Django", "Node.js", "NestJS"],
            "infra": ["Docker", "Linux", "Vercel"]
        }
    
    def objetivo(self):
        return "Construir soluções escaláveis e limpas."

meu_perfil = Desenvolvedor()
