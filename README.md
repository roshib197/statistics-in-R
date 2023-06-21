# Crear un vector numérico
mi_vector_num <- c(1, 2, 3, 4, 5)
# Graficar el vector
plot(mi_vector_num)


# Crear un vector numérico
mi_vector_num <- c(1, 2, 3, 4, 5)
# Calcular la media y la desviación estándar del vector
media <- mean(mi_vector_num)
desviacion_estandar <- sd(mi_vector_num)
media
desviacion_estandar
# Graficar un histograma del vector
hist(mi_vector_num)


# Crear dos vectores numéricos
x <- c(1, 2, 3, 4, 5)
y <- c(2, 4, 6, 8, 10)
# Realizar una regresión lineal
modelo <- lm(y ~ x)
# Graficar los puntos y la línea de regresión
plot(x, y)
abline(modelo)


# Crear tres vectores numéricos
grupo1 <- c(1, 2, 3, 4, 5)
grupo2 <- c(2, 4, 6, 8, 10)
grupo3 <- c(3, 6, 9, 12, 15)
# Realizar un ANOVA
modelo <- aov(c(grupo1, grupo2, grupo3) ~ rep(1:3, each = 5))
# Graficar un diagrama de cajas
boxplot(grupo1, grupo2, grupo3)
