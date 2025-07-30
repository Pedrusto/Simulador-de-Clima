# Simulador de Clima - Python

Este projeto é um **Simulador de Clima** que utiliza a API do [OpenWeather](https://openweathermap.org/) para coletar dados meteorológicos atuais e previsões para os próximos 5 dias de uma cidade específica, exibindo gráficos interativos de temperatura e umidade.

> **Este código foi desenvolvido para um projeto acadêmico, com foco em aprendizado e aplicações de funções em Python.  
> O objetivo é proporcionar entendimento sobre integração com APIs, manipulação e análise de dados, além de técnicas de visualização gráfica.**

## Funcionalidades

- Busca condições climáticas **atuais** de uma cidade.
- Obtém **previsão** de temperatura mínima, máxima e umidade para os próximos 5 dias.
- Calcula estatísticas básicas (médias de temperatura e umidade).
- Exibe gráficos interativos para visualização dos dados.
- Fácil de adaptar para outras cidades.

## Requisitos

- Python 3.7+
- [requests](https://pypi.org/project/requests/)
- [pandas](https://pypi.org/project/pandas/)
- [matplotlib](https://pypi.org/project/matplotlib/)
- [numpy](https://pypi.org/project/numpy/)
- Chave de API do OpenWeather (crie gratuitamente em [openweathermap.org](https://home.openweathermap.org/users/sign_up))

## Instalação

1. **Clone o repositório:**
   ```bash
   git clone https://github.com/Pedrusto/simulador-de-clima.git
   cd simulador-de-clima
   ```

2. **Instale as dependências:**
   ```bash
   pip install requests pandas matplotlib numpy
   ```

3. **Configure a chave da API:**
   - No arquivo `SimuladorDeClima.py`, substitua o valor de `api_key` pela sua chave obtida no OpenWeather.

## Uso

No terminal:
```bash
python SimuladorDeClima.py
```

Por padrão, o exemplo utiliza os dados da cidade de **Maceió**. Para utilizar outra cidade, altere o dicionário `city` no final do arquivo:

```python
city = {'nome': 'NomeDaCidade', 'lat': LATITUDE, 'lon': LONGITUDE}
```

## Exemplo de Saída

- Gráfico de Temperatura (mínima, máxima e atual)
- Gráfico de Umidade (prevista e atual)
- Estatísticas médias exibidas no console

## Licença

Este projeto está sob a licença MIT.

---

## Autor

- [Pedro Augusto](https://github.com/Pedrusto)