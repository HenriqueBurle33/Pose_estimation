# Pose_estimation

## Resultados
- Na maioria dos casos o modelo falhou em identificar landmarks anatomicos nos Bovinos, em alguns casos quando tinha uma pessoa perto a predição acontecia na pessoa e não no animal. Isso ja era esperado pois o modelo foi treinado para fazer o Pose Estimation em humanos.

### Conclusões
O **MediaPipe Pose** foi ineficiente na detecção de landmarks em animais, claramente possui limitações devido ao fato de ser projetado para humanos. 

### Limitações e Trabalhos Futuros
- **Limitações:** O modelo não é específico para animais, o que reduz a precisão.
- **Futuro:** Um modelo treinado para anatomia animal melhoraria os resultados. Explorar vídeos e outras classes de animais pode ser um próximo passo interessante.
