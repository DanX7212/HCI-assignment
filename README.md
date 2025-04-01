* HTML code

<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<style>
h1, p, td {
  text-align: center;
}
img {
  width: 100%;
  height: 150px;
}
</style>
</head>
<body>
<h1>ONLINE SHOPPING</h1>
<table width="100%">
  <tr>
    <td width="30%">
      <table width="100%">
        <tr>
          <td>
            <p><a href="https://www.lazada.com/" target="_blank"><img src="images/Lazada (2019).svg" border="1px"></a></p>
            <p><a href="https://www.lazada.com/" target="_blank">lazada.com</a></p>
          </td>
        </tr>
        <tr>
          <td>
            <p><a href="https://www.shopee.com/" target="_blank"><img src="images/Shopee-logo.jpg" border="1px"></a></p>
            <p><a href="https://www.shopee.com/" target="_blank">shopee.com</a></p>
          </td>
        </tr>
        <tr>
          <td>
            <p><a href="https://www.shein.com/" target="_blank"><img src="images/Shein-logo.png" border="1px"></a></p>
            <p><a href="https://www.shein.com/" target="_blank">shein.com</a></p>
          </td>
        </tr>
      </table>
    </td>
    <td width="70%">
      <iframe src="demo.htm" id="iframe" name="a" height="600px" width="100%"></iframe>
    </td>
  </tr>
</table>
</body>
</html>

* CSS code

.container {
  display: flex;
  flex-wrap: wrap; /* Allow items to wrap onto multiple lines */
  justify-content: space-around; /* Distribute items evenly */
  padding: 20px;
}

.item {
  width: 300px; /* Adjust width as needed */
  margin-bottom: 20px;
  border: 1px solid #ccc;
  padding: 10px;
  text-align: center;
}

.item img {
  max-width: 100%;
  height: auto;
}

/* Style for specific items (adjust as needed) */
.Lazada (2019).svg {
  order: -1; /* Put Lazada logo at the top */
  text-align: center;
  font-size: 3em;
  font-weight: bold;
  width: 100%;
}

.button {
  background-color: #4CAF50; /* Green */
  border: none;
  color: white;
  padding: 15px 32px;
  text-align: center;
  text-decoration: none;
  display: inline-block;
  font-size: 16px;
  margin: 4px 2px;
  cursor: pointer;
}

