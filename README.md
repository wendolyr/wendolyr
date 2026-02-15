<h1 align="center" style="font-size: 3em;">💻 C++ / Golang разработчик</h1>

### О себе  

🚀 **Сейчас**:  
- 💼 C++ десктоп-разработчик в **Яндекс Диске**  
- 🎓 Студент **Школы 21** от Сбера  

🔧 **Инженерный опыт → Разработка ПО**:  
- 🛢️ **Магистр нефтегазового дела и экономики**  
- ⛏️ **3 года работал инженером по бурению в Роснефти**  
- 💡 **В разработке** с 2024 года  

## 🛠️ **Ключевые навыки**  
#### 💻 Языки
![C++](https://img.shields.io/badge/-C++-00599C?logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/-C-A8B9CC?logo=c&logoColor=white)
![Go](https://img.shields.io/badge/-Go-00ADD8?logo=go&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white)

#### 🧩 Фреймворки
![Qt](https://img.shields.io/badge/-Qt-41CD52?logo=qt&logoColor=white)

#### 🗄️ Базы данных
![PostgreSQL](https://img.shields.io/badge/-PostgreSQL-4169E1?logo=postgresql&logoColor=white)

#### ⚙️ Инструменты и технологии
![Git](https://img.shields.io/badge/-Git-F05032?logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/-Linux-FCC624?logo=linux&logoColor=black)
![CI/CD](https://img.shields.io/badge/-CI/CD-FF6B6B?logo=githubactions&logoColor=white)

## 🎸 **Хобби & Интересы**  

<div>
  
```cpp
#include <memory>

class Hobby {
public:
    virtual void execute() = 0;
    virtual ~Hobby() = default;
};

class AlgorithmSolving : public Hobby {
public:
    void execute() override {
        find_optimal_solution();
    }
};

class GuitarPlaying : public Hobby {
public:
    void execute() override {
        play_rock_music();
    }
};

class BookReading : public Hobby {
public:
    void execute() override {
        read_fiction();
    }
};

class HobbyContext {
    std::unique_ptr<Hobby> strategy_;
public:
    void setStrategy(std::unique_ptr<Hobby> strategy) {
        strategy_ = std::move(strategy);
    }
    
    void FreeTime() {
        if (strategy_) {
            strategy_->execute();
        }
    }
};
```
</div>

## 🏆 Прогресс в LeetCode
<br/>
<a href="https://leetcode.com/wendolyr/">
  <p align="center">
    <img width="400" height="200" src="https://leetcard.jacoblin.cool/wendolyr">
  </p>
</a>
<br/>
