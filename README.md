# CodingBatWarmup
sleepIn
public boolean sleepIn(boolean weekday, boolean vacation) {
  if (!weekday || vacation) {
    return true;
  }
    return false; 
}

monkeyTrouble
public boolean monkeyTrouble(boolean aSmile, boolean bSmile) {
  if ((aSmile && bSmile) || (!aSmile && !bSmile)) {
    return true;
  }
  return false;
}

sumDouble
public int sumDouble(int a, int b) {
  int sum = a + b;
  if (a != b) {
    return sum;
  }
  return sum * 2;
}

diff21
public int diff21(int n) {
  if (n > 21) {
    return (n-21) * 2;
  }
  return 21-n;
}

parrotTrouble
public boolean parrotTrouble(boolean talking, int hour) {
  if (talking && (hour < 7 || hour > 20)) {
    return true;
  }
  return false;
}

makes10
public boolean makes10(int a, int b) {
  if ((a ==10 || b==10) || (a + b == 10)) {
    return true;
  }
  return false;
}

nearHundred
public boolean nearHundred(int n) {
  return ((Math.abs(100 - n) <= 10) || (Math.abs(200 - n) <= 10));
}

posNeg
public boolean posNeg(int a, int b, boolean negative) {
  if (!negative) {
    return ((a < 0 && b > 0) || (a > 0 && b <0));
  }
  return (a < 0 && b <0);
}

notString
public String notString(String str) {
  if (str.length() >= 3 && str.substring(0, 3).equals("not")) {
    return str;
  }
  return "not " + str;
}

