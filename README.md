1. install  Anaconda 5.0.1 (Python 3.6)
1. install [Redis](https://github.com/MicrosoftArchive/redis)
1. inside anaconda promp (with admin priv):
    1. `conda create --name bombtag python=3.6`
    1. `mkdir bombtag && cd bombtag`
    1. `activate bombtag`
    1. `pip install SerpentAI`
    1. `serpent setup`
    1. `serpent generate game`
        > BombTag
    1. `pip install pypiwin32`
    1. Change `WINDOW_NAME` to `BombTag`
    1. Change `APP_ID` to `791930`
    1. `serpent generate game_agent`
