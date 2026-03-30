# calendar-
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>April 2009 Calendar</title>
<style>
    body {
        font-family: "Comic Sans MS", cursive, sans-serif;
        background-color: #ffeef5;
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }

    .calendar {
        background: #fff;
        border-radius: 20px;
        box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        padding: 20px;
        width: 320px;
        text-align: center;
    }

    .month {
        font-size: 24px;
        color: #ff69b4;
        margin-bottom: 10px;
    }

    .days, .dates {
        display: grid;
        grid-template-columns: repeat(7, 1fr);
    }

    .days div {
        font-weight: bold;
        color: #ff85a2;
        margin-bottom: 5px;
    }

    .dates div {
        padding: 10px;
        margin: 3px;
        border-radius: 10px;
        background-color: #fff0f6;
        transition: 0.3s;
    }

    .dates div:hover {
        background-color: #ffd6e8;
        cursor: pointer;
    }

    .today {
        background-color: #ffb6c1 !important;
        color: white;
        font-weight: bold;
    }
</style>
</head>
<body>

<div class="calendar">
    <div class="month">April 2009 🌸</div>

    <div class="days">
        <div>Sun</div><div>Mon</div><div>Tue</div>
        <div>Wed</div><div>Thu</div><div>Fri</div><div>Sat</div>
    </div>

    <div class="dates">
        <!-- April 2009 starts on Wednesday -->
        <div></div><div></div><div></div>
        <div>1</div><div>2</div><div>3</div><div>4</div>
        <div>5</div><div>6</div><div>7</div><div>8</div><div>9</div><div>10</div><div>11</div>
        <div>12</div><div>13</div><div>14</div><div>15</div><div>16</div><div>17</div><div>18</div>
        <div>19</div><div>20</div><div>21</div><div>22</div><div>23</div><div>24</div><div>25</div>
        <div>26</div><div>27</div><div>28</div><div>29</div><div>30</div>
    </div>
</div>

</body>
</html>
