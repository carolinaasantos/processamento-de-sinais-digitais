# Trabalhos da Disciplina Processamento de Sinais Digitais

Os trabalhos presentes neste repositório foram desenvolvidos durante a disciplina de Processamento de Sinais Digitais da Universidade Federal de São Carlos (UFSCar), no semestre 2025.1.

A disciplina teve como objetivo apresentar os principais conceitos, técnicas e aplicações da área, abordando os seguintes conteúdos:

- Filtro de Gabor: detecta padrões em diferentes frequências e direções; usado em texturas, reconhecimento facial e extração de características.
- Filtro Gaussiano: filtro passa-baixas que suaviza imagens e reduz ruídos de alta frequência.
- Filtro de Mediana: filtro não linear que remove ruído impulsivo ("sal e pimenta") preservando melhor as bordas.
- Filtros de bordas: identificam mudanças de intensidade usando derivadas e convolução.
- Filtros FIR: possuem resposta ao impulso finita, são estáveis e podem ter fase linear; podem ser projetados usando janelas (Hamming, Blackman) ou Parks-McClellan.
- Filtros IIR: filtros recursivos que geralmente exigem menos processamento que FIR, mas podem apresentar problemas de estabilidade.
- DFT/FFT: transformam o sinal do domínio do tempo para o domínio da frequência; a FFT calcula a DFT de forma eficiente.
- STFT: aplica FFT em janelas sucessivas para analisar como as frequências variam ao longo do tempo; gera espectrogramas.
- Transformada Z: usada em sinais e sistemas digitais para analisar polos, zeros e estabilidade de sistemas LTI.
- Convolução: combina o sinal de entrada com a resposta ao impulso de um filtro ou sistema para determinar sua saída.
- Correlação: mede a semelhança entre sinais; inclui correlação cruzada e autocorrelação e é usada em radar, sonar e filtros casados.
- Janelamento: multiplica um trecho do sinal por uma função, como Kaiser, Hann ou Bartlett, para reduzir o vazamento espectral antes de aplicar transformadas.
- Amostragem (Nyquist-Shannon): para representar corretamente um sinal limitado a ($f_{max}$), a frequência de amostragem deve ser maior que $2(f_{max})$. Caso contrário, pode ocorrer aliasing.
