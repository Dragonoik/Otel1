<!DOCTYPE HTML>
<html>
 <head>
  <title>БРОНЬ</title>
 </head>
 <body>
 <h1>Бронь отеля</h1>
 <hr>
 <form>
  <fieldset>
   <legend>Ваши данные</legend>
   Ваше имя:
   <input required type="text">
   <p>Ваша фамилия:
   <input required type="text"></p>
   Ваш пол:
   <select name="пол">
    <option>Мужчина</option>
    <option>Женщина</option>    
   </select>
   <p>Дата рождения:
   <input type="date"></p>
   <p>Ваш e-mail:
   <input required type="text"></p>
   <p>Номер телефона:
   <input required type="number"></p>
   <p><input type="submit" name="данные" value="Подтвердить"></p>
  </fieldset> 
 </form>
 <form>
   <fieldset>
   <legend>Общие данные</legend>
   <p>Сколько будет взрослых? (включая вас)</p>
   <input required type="radio" name="1" value="1">1
   <input type="radio" name="1" value="1">2
   <input type="radio" name="1" value="1">3
   <input type="radio" name="1" value="1">4
   <input type="submit" name="1" value="Подтвердить">
   <p>Сколько будет детей?</p>
   <input type="radio" name="1" value="1">0
   <input type="radio" name="1" value="1">1
   <input type="radio" name="1" value="1">2
   <input type="radio" name="1" value="1">3
   <input type="radio" name="1" value="1">4
   <input type="radio" name="1" value="1">5
   <input type="submit" name="1" value="Подтвердить">
   <p>Среди вас есть курящие?</p>
   <input type="checkbox" name="1" value="1">Да, желаем приобрести номер для курящих.
   <input type="reset" name="1" value="Стереть">
   <p>Можно ли вас заселить в разные номера если не будет подходящих?</p>
   <input type="checkbox" name="1" value="1">Да.
   <input type="reset" name="1" value="Стереть">
   </fieldset>
  </form>
  <form>
   <fieldset>
   <legend>Укажите время заселения.</legend>
   Укажите дату.
   <input required type="date">
   Укажите время.
   <input required type="time">
   </fieldset>
  </form>
  <form>
   <fieldset>
   <legend>По желанию оставьте комментарий.</legend>
   <textarea placeholder="Ваш комментарий" rows="10" cols="45" name="text"></textarea>
   </fieldset>
  </form>
 </body>
</html>
