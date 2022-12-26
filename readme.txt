
main до service we provide MOBILE XS
.main {
  display: flex;
  flex-direction: column;
  row-gap: 50px;
}

.container-fluid {
  width: 100%;
}

.general {
  background: url(./img/pictures/flower-bg.png) no-repeat,
    linear-gradient(
      79.58deg,
      rgba(0, 115, 12, 0.579) -39.14%,
      rgba(251, 246, 238, 0) 90.23%
    );
  background-position: 0 100%;
  display: flex;
  flex-direction: column-reverse;
  color: #212529;
}
.general .content {
  padding: 0 15px;
}
.general .content .subtitle {
  font-weight: 700;
  font-size: 14px;
  margin-top: 48px;
  display: flex;
  align-items: center;
}
.general .content .subtitle::before {
  content: url(./img/icons/main/leaves.svg);
  padding-right: 5px;
}
.general .content .title {
  margin-top: 10px;
}
.general .content .paragraph {
  margin-top: 15px;
}
.general .content .buttons {
  margin-top: 40px;
  display: flex;
  flex-direction: column;
  align-items: center;
}
.general .content .buttons .button {
  background-color: #00730c;
  border: 1px solid #00730c;
  border-radius: 5px;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #ffffff;
  font-weight: 700;
  padding: 0;
  width: calc(100% - 44px);
  height: 44px;
  font-size: 16px;
  line-height: 20px;
  text-transform: capitalize;
}
.general .content .buttons .link {
  margin-top: 19px;
  font-weight: 600;
  font-size: 14px;
  color: #00730c;
}
.general .content .buttons .link::after {
  content: url(./img/icons/main/arrow-next.svg);
  padding-left: 10px;
}
.general .content .tags-s {
  display: flex;
  justify-content: flex-end;
  color: #212529;
  margin-bottom: 35px;
  margin-top: 40px;
}
.general .content .tags-s .tag {
  width: calc(50% - 60px);
  height: 32px;
  background: linear-gradient(180deg, #fff8f1 0%, #cbe5ce 100%);
  border-radius: 16px;
  margin-left: 10px;
  font-weight: 400;
  font-size: 10px;
  line-height: 32px;
  text-align: center;
}
.general .content .tags-s .tag span {
  font-weight: 700;
  font-size: 12px;
}
.general .content .tags-l {
  display: none;
}

section .title {
  font-size: 28px;
  line-height: 38px;
  font-weight: 700;
}
section .title span {
  color: #00730c;
}
section .paragraph {
  font-weight: 400;
  font-size: 14px;
  line-height: 22px;
}

main до service we provide MOBILE XS