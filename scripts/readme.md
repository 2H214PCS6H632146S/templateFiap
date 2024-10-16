create table InformacoesCulturas(
    id NUMBER GENERATED ALWAYS AS IDENTITY PRIMARY KEY,
    tipo_cultura VARCHAR2(30),
    umidade_ar FLOAT,
    ph_solo FLOAT,
    temperatura FLOAT,
    NDMI FLOAT
);
