# StringParser
  public static string GetNid(string nidInfo)
        {
            string nid = null;
            if (nidInfo.Contains("ID NO:"))
            {
                nid = nidInfo.Substring(nidInfo.IndexOf("ID NO: ") + 7).Split(' ')[0];
            }
            return nid;
        }
        //write this code in controller
        //string text1 = nidInfo;
        //text1 = Regex.Replace(text1, @"\s+", " ");

        //    string nid = GlobalMethods.GetNid(text1.Trim());
        //var length = nid.Length;
