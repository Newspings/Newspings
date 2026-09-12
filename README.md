<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Newspings FX</title>

<style>

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, Helvetica, sans-serif;
    background: #06101c;
    color: #ffffff;
}

header {
    background: #081827;
    border-bottom: 1px solid #1b344c;
    padding: 20px 7%;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.logo {
    font-size: 25px;
    font-weight: 800;
    letter-spacing: 1px;
}

.logo span {
    color: #20d6a3;
}

nav a {
    color: #d8e2eb;
    text-decoration: none;
    margin-left: 22px;
    font-size: 14px;
}

nav a:hover {
    color: #20d6a3;
}

.hero {
    min-height: 620px;
    padding: 90px 7%;
    display: flex;
    align-items: center;
    background:
        radial-gradient(circle at 80% 30%, #12395b 0%, transparent 35%),
        linear-gradient(135deg, #06101c, #0b2136);
}

.hero-content {
    max-width: 760px;
}

.badge {
    display: inline-block;
    padding: 9px 15px;
    border: 1px solid #20d6a3;
    border-radius: 30px;
    color: #20d6a3;
    font-size: 12px;
    margin-bottom: 25px;
}

.hero h1 {
    font-size: 58px;
    line-height: 1.05;
    margin-bottom: 25px;
}

.hero h1 span {
    color: #20d6a3;
}

.hero p {
    color: #aabaca;
    font-size: 18px;
    line-height: 1.7;
    margin-bottom: 32px;
}

.buttons {
    display: flex;
    gap: 14px;
    flex-wrap: wrap;
}

.button {
    display: inline-block;
    padding: 15px 25px;
    border-radius: 8px;
    text-decoration: none;
    font-weight: bold;
}

.button-main {
    background: #20d6a3;
    color: #03120e;
}

.button-second {
    border: 1px solid #385570;
    color: white;
}

section {
    padding: 75px 7%;
}

.section-title {
    text-align: center;
    margin-bottom: 45px;
}

.section-title h2 {
    font-size: 35px;
    margin-bottom: 10px;
}

.section-title p {
    color: #91a4b8;
}

.market-grid {
    display: grid;
    grid-template-columns: repeat(4, 1fr);
    gap: 20px;
}

.market {
    background: #0b1b2c;
    border: 1px solid #1d3852;
    border-radius: 14px;
    padding: 25px;
}

.market h3 {
    margin-bottom: 18px;
}

.price {
    font-size: 25px;
    font-weight: bold;
    margin-bottom: 8px;
}

.green {
    color: #20d6a3;
}

.red {
    color: #ff6577;
}

.features {
    background: #091727;
}

.feature-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 20px;
}

.feature {
    background: #0d1e31;
    border: 1px solid #1d3852;
    border-radius: 14px;
    padding: 30px;
}

.feature-icon {
    font-size: 32px;
    margin-bottom: 18px;
}

.feature h3 {
    margin-bottom: 12px;
}

.feature p {
    color: #95a9bd;
    line-height: 1.6;
}

.register {
    background: linear-gradient(135
