unit Unit1;

{$mode objfpc}{$H+}

interface

uses
  Classes, SysUtils, FileUtil, Forms, Controls, Graphics, Dialogs, StdCtrls,
  ExtCtrls;

type

  { TForm1 }

  TForm1 = class(TForm)
    Edit1: TEdit;
    Edit10: TEdit;
    Edit11: TEdit;
    Edit2: TEdit;
    Edit3: TEdit;
    Edit4: TEdit;
    Edit5: TEdit;
    Edit6: TEdit;
    Edit7: TEdit;
    Edit8: TEdit;
    Edit9: TEdit;
    Image1: TImage;
    Image2: TImage;
    bluebutton: TImage;
    greenbutton: TImage;
    buttonnext: TImage;
    buttonback: TImage;
    titleoftheme: TLabel;
    redbutton: TImage;
    Label1: TLabel;
    Label2: TLabel;
    StaticText1: TStaticText;
    StaticText2: TStaticText;
    StaticText3: TStaticText;
    procedure bluebuttonClick(Sender: TObject);
    procedure Button1Click(Sender: TObject);
    procedure Button2Click(Sender: TObject);
    procedure Button3Click(Sender: TObject);
    procedure buttonbackClick(Sender: TObject);
    procedure FormShow(Sender: TObject);
    procedure greenbuttonClick(Sender: TObject);
    procedure Image1Click(Sender: TObject);
    procedure buttonnextClick(Sender: TObject);
    procedure Image2Click(Sender: TObject);
    procedure Panel1Click(Sender: TObject);
    procedure redbuttonClick(Sender: TObject);
    procedure titleofthemeClick(Sender: TObject);
  private
    { private declarations }
  public
    { public declarations }
  end;

var
  Form1: TForm1;
  i:integer;

implementation

 uses unit2;
{$R *.lfm}

{ TForm1 }

procedure TForm1.Button1Click(Sender: TObject);
begin

end;

procedure TForm1.bluebuttonClick(Sender: TObject);
begin
  for i:=1 to 10 do begin
     if i=1 then begin if edit1.caption<>'' then begin edit1.caption:=edit2.caption; end; end;
     if i=2 then begin if edit2.caption<>'' then begin edit2.caption:=edit3.caption; end; end;
     if i=3 then begin if edit3.caption<>'' then begin edit3.caption:=edit4.caption; end; end;
     if i=4 then begin if edit4.caption<>'' then begin edit4.caption:=edit5.caption; end; end;
     if i=5 then begin if edit5.caption<>'' then begin edit5.caption:=edit6.caption; end; end;
     if i=6 then begin if edit6.caption<>'' then begin edit6.caption:=edit7.caption; end; end;
     if i=7 then begin if edit7.caption<>'' then begin edit7.caption:=edit8.caption; end; end;
     if i=8 then begin if edit8.caption<>'' then begin edit8.caption:=edit9.caption; end; end;
     if i=9 then begin if edit9.caption<>'' then begin edit9.caption:=edit10.caption; end; end;
     if i=10 then begin if edit10.caption<>'' then begin edit10.caption:=''; label2.Visible:=false; end; end;   end;
  if (edit1.Caption='') then begin label2.visible:=true; label2.caption:='Очередь пуста'; end;
end;

procedure TForm1.Button2Click(Sender: TObject);
begin

end;

procedure TForm1.Button3Click(Sender: TObject);
begin

end;

procedure TForm1.buttonbackClick(Sender: TObject);
begin
  form1.hide;
  form2.show;
end;

procedure TForm1.FormShow(Sender: TObject);
var
  randomButton : TButton;
begin
  randomButton := TButton.Create(Form1);
  randomButton.Parent := Form1;
  randomButton.top := 100;
  randomButton.Left:= 100;
  randomButton.Width:= 300;
  randomButton.Height:= 300;
  randomButton.Caption:= '777 Тритопора';
end;


procedure TForm1.greenbuttonClick(Sender: TObject);
begin
  for i:=1 to 10 do begin
     if i=1 then begin if edit1.caption='' then begin edit1.caption:=inttostr(random(9)); label2.visible:=false; break; end; end;
     if i=2 then begin if edit2.caption='' then begin edit2.caption:=inttostr(random(9)); break; end; end;
     if i=3 then begin if edit3.caption='' then begin edit3.caption:=inttostr(random(9)); break; end; end;
     if i=4 then begin if edit4.caption='' then begin edit4.caption:=inttostr(random(9)); break; end; end;
     if i=5 then begin if edit5.caption='' then begin edit5.caption:=inttostr(random(9)); break; end; end;
     if i=6 then begin if edit6.caption='' then begin edit6.caption:=inttostr(random(9)); break; end; end;
     if i=7 then begin if edit7.caption='' then begin edit7.caption:=inttostr(random(9)); break; end; end;
     if i=8 then begin if edit8.caption='' then begin edit8.caption:=inttostr(random(9)); break; end; end;
     if i=9 then begin if edit9.caption='' then begin edit9.caption:=inttostr(random(9)); break; end; end;
     if i=10 then begin if edit10.caption='' then begin edit10.caption:=inttostr(random(9)); label2.visible:=true; label2.caption:='Очередь переполнена (в данном примере)'; break; end; end;

  end;
end;

procedure TForm1.Image1Click(Sender: TObject);
begin

end;

procedure TForm1.buttonnextClick(Sender: TObject);
begin
  titleoftheme.caption:='Упражнение №1';
  label1.Caption:='Другое задание';
  StaticText1.Caption:='';
  StaticText2.Caption:='';
  StaticText3.Caption:='';
end;

procedure TForm1.Image2Click(Sender: TObject);
begin

end;

procedure TForm1.Panel1Click(Sender: TObject);
begin

end;

procedure TForm1.redbuttonClick(Sender: TObject);
begin
  edit11.caption:=edit1.caption;
end;

procedure TForm1.titleofthemeClick(Sender: TObject);
begin

end;

end.

