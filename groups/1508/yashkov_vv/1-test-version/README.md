# �������� ������ �������� ������ ���������� ����������

## ��������� �������

1. solver
- before_code.cpp - �������� ������ ������ �� ��������� �����, ������ ������ ���������� �����, ������ ���������� ������ � �������� ����
- solver.cpp - �������� ���������������� ���������� ������� ������ ���������� ����� �� ����� ����� (������� ����)
2. generator.cpp - ��������� ��� ������������� �������� ������, ���������� �������� �������

3. checker.cpp - ��������� ��� �������� ������������ ������

4. viewer.cpp - ��������������� ���������, ������ ��� �������� ��������� �����, ����������� ������, � ���������

5. typer.cpp - ��������������� ���������, ������ ��� �������� ���������� �����, ����������� ������, � ��������


## ������ ����� ������

1. ������� ������ �� 'input file', ������������� � �������� ��������� � 'output file'
- solver <input file> <output file>
����������: input file ������ ���� �������� (��������������� ��� ������ generator ��� typer)

2. ������������� ����
- generator <test number (1 - 20)> <output binary file> <answer binary file>
�� ������ ����� ������� ����� ������ � ��������������� �����. ��� ������ �����, ��� ������ ����� ������.
������ ����� ����� �������� � output binary file, � ���������� � ���������� ����� � answer binary file

3. ��������� ������������ ��������� ���������� �����
- checker <output binary file> <answer binary file>
����������: output binary file � answer binary file ������� ���� ��������� �������, ���������� ��� ������ solver'�.

4. ��������� ��������� ����, ���������� ������, � ��������
- typer <input file> <output file>
����������: input file ������ ��������� �������� �������, ������ ������� ������ ������������� �� ����� ������.

5. ��������� �������� ����, ���������� ������, � ���������
- viewer <input file> <output file>


## ������� �������� ����� � ������� �����

1. ������������ ��������� generator
2. ������ ������ ������� � ��������� ���� � ��� ������ typer ��������� � �������� ������