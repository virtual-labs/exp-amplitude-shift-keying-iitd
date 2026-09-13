<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="p-6">

  <p class="mb-6 text-[18px] leading-relaxed">
    Digital modulation schemes are techniques used to encode information onto a carrier signal by varying
    its properties according to discrete symbols. The three fundamental digital modulation techniques are
    Amplitude Shift Keying (ASK), Frequency Shift Keying (FSK), and Phase Shift Keying (PSK).
  </p>

  <p class="mb-4 text-[18px] leading-relaxed">
    <b>Amplitude Shift Keying (ASK)</b> is the simplest form of digital modulation. In this technique, the
    amplitude of a carrier signal is varied according to the binary input. Typically, a carrier is transmitted
    for a binary '1' and turned OFF for a binary '0', a method also known as On-Off Keying (OOK). ASK was one
    of the earliest modulation schemes used in wireless communication systems.
  </p>

  <p class="mb-4 text-[18px] leading-relaxed">
    In <b>Frequency Shift Keying (FSK)</b>, digital data is represented by shifting the frequency of the carrier
    signal between two distinct values. For example, a higher frequency (f₁) may represent binary '1', while a
    lower frequency (f₂) represents binary '0'. The amplitude of the signal remains constant while only the
    frequency changes.
  </p>

  <p class="mb-6 text-[18px] leading-relaxed">
    In <b>Phase Shift Keying (PSK)</b>, the phase of the carrier signal is varied to represent digital data.
    In Binary Phase Shift Keying (BPSK), a binary '1' is represented by a carrier with a reference phase,
    while a binary '0' is represented by a carrier shifted by 180 degrees (π radians). This makes PSK more
    robust to noise compared to ASK.
  </p>

  <h4 class="text-2xl font-semibold mb-4">Digital Modulation Techniques</h4>

  <ol class="mb-4 pl-6 list-decimal text-[#007bff] text-[18px]" style="font-family: Raleway, sans-serif">
    <li class="mb-2">
      <a href="./ASK.html" class="hover:text-[#3e6389] hover:underline">
        Amplitude Shift Keying (ASK)
      </a>
    </li>
    <li class="mb-2">
      <a href="./FSK.html" class="hover:text-[#3e6389] hover:underline">
        Frequency Shift Keying (FSK)
      </a>
    </li>
    <li class="mb-2">
      <a href="./PSK.html" class="hover:text-[#3e6389] hover:underline">
        Phase Shift Keying (PSK)
      </a>
    </li>
  </ol>

</body>
</html>
