���ԣ�������Converter������һЩ�򵥵�c#�﷨

Debug.Assert(Test("True||False").ToString() == "True");
Debug.Assert(Test("True?111:222").ToString() == "111");

Debug.Assert(Test("(bool)True||False").ToString() == true.ToString());
Debug.Assert(Test("(int)True?111:222").ToString() == 111.ToString());
Debug.Assert(Test("(bool)1>2").ToString() == false.ToString());
Debug.Assert(Test("(bool)1<2").ToString() == true.ToString());