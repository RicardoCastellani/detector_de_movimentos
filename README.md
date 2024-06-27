# Detector de Movimento com OpenCV e Tkinter

Este repositório contém um simples detector de movimento utilizando Python com OpenCV para captura de vídeo e Tkinter para a interface gráfica. O detector monitora a diferença entre frames consecutivos da webcam para identificar movimentos e captura imagens quando detecta alterações significativas.

## Funcionalidades

- **Detecção de Movimento:** Utiliza a técnica de subtração de pixels para identificar mudanças entre frames.
- **Captura de Imagens:** Salva imagens quando movimento é detectado em tempo real.
- **Interface Gráfica Simples:** Botão para iniciar a detecção e mensagem informativa.

## Instruções de Uso

1. Clone o repositório.
2. Certifique-se de ter Python e as bibliotecas necessárias instaladas (OpenCV e Tkinter).
3. Execute o arquivo `detector_movimento.py`.
4. Pressione o botão "Ligar Detector de Movimento" para iniciar a detecção.
5. Para encerrar, pressione a tecla 'Esc'.

## Estrutura do Repositório

- `detector_movimento.py`: Código fonte principal.
- `README.md`: Este arquivo, contendo instruções básicas.

## Requisitos

- Python 3.x
- OpenCV
- Tkinter

## Notas

- O código captura imagens automaticamente quando movimento é detectado e as salva em um diretório específico (`C:\Imagens Deteccao/`).

