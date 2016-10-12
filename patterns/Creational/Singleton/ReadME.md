**`Одиночка`** (англ. Singleton) — порождающий шаблон проектирования, позволяет содержать только один экземпляр объекта в приложении, 
которое будет обрабатывать все обращения, запрещая создавать новый 
экземпляр.

**`Применение`:**
Для некоторых классов важно, чтобы существовал только один экземпляр. Хотя
в системе может быть много принтеров, но возможен лишь один спулер.
Должны быть только одна файловая система и единственный оконный менеджер.
В цифровом фильтре может находиться только один аналого-цифровой преобразователь(АЦП). Бухгалтерская система обслуживает только одну компанию