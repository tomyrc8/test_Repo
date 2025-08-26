Este es mi repo y es mi primer cambio
// href - Retorna la URL de la pagina actual
// console.log(window.location.href); //si quiero le puedo sacar el 'window' y funciona igual.

// hostname - Retorna el host de la pagina actual
// console.log(location.hostname); //nos devuelve una cadena vacia porque no estamos trabajando con servidor. Para probarlo lo hago desde la consola de la pagina de google

// pathname - Retorna la ruta y archivo de la pagina actual
// console.log(location.pathname);

// protocol - Retorna el protocolo utilizado
// console.log(location.protocol);

// assing - Te permite cargar otros documentos pj google.com
const cargarDocumento = () => {
    location.assign('https://google.com');
};

// history.back() - Te permite ir hacia atras
const regresar = () => {
    history.back();
};

// history.forward() - Te permite ir hacia adelante
const irAdelante = () => {
    history.forward();
};