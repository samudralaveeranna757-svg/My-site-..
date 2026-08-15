<!DOCTYPE html>
<html>
<head>
    <title>Competitive Exam Application</title>

    <style>
        body {
            font-family: Arial;
            background: #f2f2f2;
            margin: 0;
            padding: 20px;
        }

        .container {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 25px;
            border-radius: 10px;
        }

        h1 {
            text-align: center;
            color: #1a4d8f;
        }

        label {
            display: block;
            margin-top: 12px;
            font-weight: bold;
        }

        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin-top: 5px;
            box-sizing: border-box;
        }

        button {
            width: 100%;
            padding: 12px;
            margin-top: 20px;
            background: #1a4d8f;
            color: white;
            border: none;
            font-size: 17px;
            border-radius: 5px;
        }

        button:hover {
            background: #12345f;
        }
    </style>
</head>

<body>

<div class="container">

    <h1>Competitive Exam Application</h1>

    <form>

        <label>Candidate Name</label>
        <input type="text" placeholder="Enter your name" required>

        <label>Father's Name</label>
        <input type="text" placeholder="Enter father's name" required>

        <label>Date of Birth</label>
        <input type="date" required>

        <label>Gender</label>
        <select>
            <option>Select Gender</option>
            <option>Male</option>
            <option>Female</option>
            <option>Other</option>
        </select>

        <label>Mobile Number</label>
        <input type="tel" placeholder="Enter mobile number" required>

        <label>School / College Name</label>
        <input type="text" placeholder="Enter school or college name">

        <label>Mandal</label>
        <input type="text" placeholder="Enter mandal">

        <label>District</label>
        <input type="text" placeholder="Enter district">

        <label>Medium</label>
        <select>
            <option>Select Medium</option>
            <option>English</option>
            <option>Telugu</option>
            <option>Hindi</option>
        </select>

        <label>Competitive Exam</label>
        <select>
            <option>Select Exam</option>
            <option>JEE</option>
            <option>NEET</option>
            <option>POLYCET</option>
            <option>ECET</option>
            <option>SSC</option>
            <option>Other</option>
        </select>

        <label>Address</label>
        <textarea rows="4" placeholder="Enter your address"></textarea>

        <button type="submit">Submit Application</button>

    </form>

</div>

</body>
</html>
