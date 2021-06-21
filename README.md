# CSS-pagination

Please see Codepen:

https://codepen.io/K-SY/pen/gOmdxeP

![image](https://user-images.githubusercontent.com/63223781/122510165-b564e880-d037-11eb-9bd8-fc8451cd7213.png)


``` css
@charset "utf-8";
/*----------------------------------------
  pagination Style
----------------------------------------*/

.pagination-wrapper {
  padding: 40px 0;
  text-align: center;
}
.pagination {
  width: auto;
  display: inline-block;
  text-align: center;
}
.pagination-wrapper .page-input {
  width: auto;
  display: inline-block;
  padding-left: 10px;
  margin: 9px 9px 9px 0;
}
.pagination ul {
  list-style: none;
  margin-left: -40px;
}
.pagination ul li {
  display: inline;
  font-size: 14px;
}
.pagination ul li a {
  color: #4d4d4d;
  text-decoration: none;
  padding: 8px 13px;
  margin: 0;
  border: none;
}
.pagination ul li.disabled a {
  padding: 8px 0px;
  cursor: not-allowed;
}
.pagination ul li.arrow a {
  border-radius: 3px;
  padding: 8px 15px;
}

.pagination ul li a:hover {
  background-color: #e8e8e8;
  border-radius: 3px;
}
.pagination ul li.disabled a:hover {
  background-color: transparent;
}
.pagination ul li.active a {
  color: #fff;
  background-color: #336899;
  border-radius: 3px;
}
.pagination-wrapper .page-input input {
  width: 30px;
  padding: 7px 6px;
  font-size: 14px;
  border: 1px solid #ccc;
  border-radius: 3px;
}
.pagination-wrapper .page-input input:focus {
  outline: none;
  border-color: #336899;
}
.pagination-wrapper .page-input span {
  font-size: 14px;
  margin-left: 4px;
}
.pagination-wrapper .page-input span a {
  color: #4d4d4d;
}
.pagination-wrapper .page-input span a:hover {
  color: #004280;
}

@media screen and (max-width: 580px) {
  .pagination ul {
    margin-left: 0px;
  }
  .pagination ul li a {
    padding: 8px 11px;
  }
  .pagination,
  .act-btn {
    padding: 25px 0;
  }
}
```
