import matplotlib.pyplot as plt

# Dados fictícios
cores = ['Vermelho', 'Azul', 'Verde', 'Amarelo', 'Outras cores']
percentagens = [30, 25, 20, 15, 10]

# Criar o gráfico de pizza
plt.figure(figsize=(8, 8))
plt.pie(percentagens, labels=cores, autopct='%1.1f%%', startangle=140)
plt.axis('equal')  # Equal garante que o gráfico seja uma circunferência
plt.title('Preferências de cores')
plt.show()
