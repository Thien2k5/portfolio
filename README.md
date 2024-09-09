Responsive:
- Đáp ứng được trên mọi device ( laptop, mobile, tablet )

h1 {
    background-color: green;
}


/* 
@media screen: code responsive cho màn hình
@media print: code responsive cho print


max-width: 400px ::: màn hình < 400px thì sẽ ăn những bộ selector bên trong
max-width: 800px

min-width: 400px ::: màn hình > 400px



Luôn luôn đặt responsive màn hình từ lớn đến bé

laptop -> tablet -> mobile
*/

/* tablet */
@media screen and (max-width: 800px) {

    h1 {
        background-color: red;
    }

}

/* mobile */
@media screen and (max-width: 400px) {

    h1 {
        background-color: yellow;
    }

}