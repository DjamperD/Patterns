**Объект-бог** (англ. God object) — антипаттерн объектно-ориентированного программирования, описывающий объект, который хранит в себе «слишком много» или делает «слишком много».

Вместо того, чтобы общаться друг с другом непосредственно, другие объекты полагаются на божественный объект. Так как на божественный объект ссылается так много кода, его обслуживание (внесение изменений) становится сложным: велик риск сломать существующую функциональность.

**Божественный объект** — это объектно-ориентированный аналог *отказа от использования подпрограмм в процедурном программировании или использования слишком большого количества глобальных переменных для хранения информации о состоянии программы*