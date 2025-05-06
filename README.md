# 📱 Intentional Tap

**Intentional Tap** é um app Android pessoal que te ajuda a **quebrar o uso automático de apps**. Toda vez que você tenta abrir um aplicativo que adicionou à lista de “protegidos”, o Intentional Tap intercepta e exibe uma tela de pausa com uma mensagem: *"Respire. Você realmente precisa abrir esse app agora?"*

Ideal para quem quer:
- Reduzir o uso impulsivo de redes sociais.
- Recuperar foco e atenção no dia a dia.
- Praticar o uso consciente do celular.

---

## ✨ Funcionalidades

✅ Adicione apps específicos (por nome do pacote) que exigirão um "respiro" antes de abrir.  
✅ Defina o tempo de espera personalizado para cada app.  
✅ Tela de pausa com bloqueio temporário.  
✅ Totalmente offline e sem rastreamento.  
✅ Interface simples, leve e escura.  
✅ Uso pessoal — sem anúncios ou cobranças.

---

## 🚀 Como funciona

1. O app monitora os aplicativos em uso (via serviço de acessibilidade).
2. Quando detecta que você está tentando abrir um app protegido:
   - Exibe uma tela de pausa com o tempo configurado.
   - Após o tempo, libera o acesso ao app original.
3. Tudo isso acontece sem interromper seu uso normal do sistema.

---

## 🛠️ Tecnologias

- React Native (JavaScript)
- Android Native (Java + AccessibilityService)
- AsyncStorage
- NativeModules

---

## 📦 Instalação (Android)

> ⚠️ Este projeto exige permissões de acessibilidade.  
> **Use por sua conta e risco.** Este app foi feito para uso pessoal.

1. Clone este repositório:
```bash
git clone https://github.com/seu-usuario/intentional-tap.git
cd intentional-tap
