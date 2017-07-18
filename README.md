# -
OnDuty
<UserControl x:Class="HighResolutionApps.VisualControls.HRVOnDutyInfo.HRVOnDutyInfo"
             xmlns="http://schemas.microsoft.com/winfx/2006/xaml/presentation"
             xmlns:x="http://schemas.microsoft.com/winfx/2006/xaml"
             xmlns:mc="http://schemas.openxmlformats.org/markup-compatibility/2006" 
             xmlns:d="http://schemas.microsoft.com/expression/blend/2008" 
             mc:Ignorable="d" Height="725" Width="406">
    <Grid>
        <Grid.RowDefinitions>
            <RowDefinition Height="1*"></RowDefinition>
            <RowDefinition Height="15*"></RowDefinition>
        </Grid.RowDefinitions>

        <Viewbox Grid.RowSpan="2" Stretch="Fill">
            <Canvas x:Name="状态窗口" Height="725.089" UseLayoutRounding="False" VerticalAlignment="Top" Margin="0,0,0,-0.089" HorizontalAlignment="Left" Width="406">
                <Canvas x:Name="图层_2" Height="725" Canvas.Left="-8" Canvas.Top="-9" Width="406">
                    <Canvas Height="725" Canvas.Left="0" Opacity="0.41"  Canvas.Top="0" Width="406">

                    </Canvas>
                    <Path Data="F1M6.913,0C3.094,0,0,3.094,0,6.912L0,383.097C0,386.915,3.094,390.009,6.913,390.009L658.867,390.009C662.684,390.009,665.779,386.915,665.779,383.097L665.779,6.912C665.779,3.094,662.684,0,658.867,0z" Height="725" Canvas.Left="0" Canvas.Top="8.422" Width="406" Stretch="Fill">
                        <Path.Fill>
                            <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                                <GradientStop Color="#FF00213D" Offset="0"/>
                                <GradientStop Color="Black" Offset="1"/>
                            </LinearGradientBrush>
                        </Path.Fill>
                        <Path.OpacityMask>
                            <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                                <GradientStop Color="#B2000000" Offset="0"/>
                                <GradientStop Color="Black" Offset="1"/>
                            </LinearGradientBrush>
                        </Path.OpacityMask>
                    </Path>
                    <Path Data="F1M7.038,0C3.157,0,0,3.156,0,7.037L0,383.222C0,387.103,3.157,390.26,7.038,390.26L658.992,390.26C662.872,390.26,666.029,387.103,666.029,383.222L666.029,7.037C666.029,3.156,662.872,0,658.992,0z M0.25,383.222L0.25,7.037C0.25,3.295,3.295,0.25,7.038,0.25L658.992,0.25C662.735,0.25,665.779,3.295,665.779,7.037L665.779,383.222C665.779,386.965,662.735,390.009,658.992,390.009L7.038,390.009C3.295,390.009,0.25,386.965,0.25,383.222" Height="725" Canvas.Left="-0.083" Canvas.Top="8.422" Width="406" Stretch="Fill">
                        <Path.Fill>
                            <LinearGradientBrush EndPoint="0,0.5" StartPoint="1,0.5">
                                <GradientStop Color="#FFFF9FA1" Offset="0"/>
                                <GradientStop Color="#FF00AAF6" Offset="0.88"/>
                                <GradientStop Color="#FF00AAF6" Offset="1"/>
                            </LinearGradientBrush>
                        </Path.Fill>
                    </Path>
                    <Path Data="F1M7.38,0.002L6.624,0.044 5.885,0.158 5.188,0.343 4.497,0.592 3.858,0.907 3.243,1.28 2.681,1.709 2.157,2.189 1.679,2.715 1.251,3.286 0.886,3.896 0.569,4.549 0.33,5.229 0.147,5.937 0.037,6.673 0,7.406 0.001,383.622 0.043,384.375 0.158,385.116 0.342,385.813 0.592,386.505 0.906,387.143 1.279,387.758 1.708,388.321 2.191,388.846 2.715,389.315 3.286,389.745 3.895,390.108 4.549,390.424 5.228,390.664 5.937,390.848 6.673,390.958 7.406,390.995 659.39,390.995 660.144,390.951 660.883,390.836 661.581,390.653 662.272,390.402 662.912,390.088 663.526,389.715 664.087,389.289 664.614,388.809 665.084,388.286 665.513,387.715 665.877,387.106 666.194,386.451 666.433,385.772 666.616,385.065 666.725,384.328 666.763,383.596 666.762,7.38 666.72,6.625 666.605,5.887 666.421,5.188 666.172,4.498 665.856,3.858 665.484,3.244 665.057,2.683 664.58,2.157 664.055,1.68 663.483,1.251 662.874,0.887 662.22,0.57 661.541,0.331 660.833,0.148 660.096,0.038 659.364,0z" Height="725" Canvas.Left="0.962" Canvas.Top="7.422" Width="406" Stretch="Fill">
                        <Path.Fill>
                            <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                                <GradientStop Color="#FF00213D" Offset="0"/>
                                <GradientStop Color="Black" Offset="1"/>
                            </LinearGradientBrush>
                        </Path.Fill>
                        <Path.OpacityMask>
                            <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                                <GradientStop Color="#B2000000" Offset="0"/>
                                <GradientStop Color="Black" Offset="1"/>
                            </LinearGradientBrush>
                        </Path.OpacityMask>
                    </Path>
                    <Path Data="F1M7.852,0.002L7.048,0.049 6.258,0.174 5.519,0.372 4.776,0.643 4.099,0.979 3.441,1.382 2.842,1.84 2.287,2.352 1.778,2.914 1.321,3.529 0.936,4.176 0.598,4.882 0.346,5.603 0.152,6.363 0.038,7.146 0,7.892 0.002,384.148 0.049,384.952 0.175,385.742 0.372,386.482 0.643,387.224 0.979,387.902 1.382,388.56 1.84,389.157 2.357,389.718 2.914,390.214 3.529,390.673 4.177,391.058 4.883,391.396 5.603,391.648 6.363,391.841 7.147,391.954 7.905,391.993 659.918,391.991 660.721,391.945 661.512,391.819 662.251,391.622 662.993,391.351 663.671,391.015 664.328,390.613 664.923,390.157 665.487,389.642 665.984,389.085 666.441,388.47 666.827,387.822 667.165,387.119 667.417,386.396 667.61,385.636 667.724,384.853 667.763,384.095 667.761,7.852 667.714,7.047 667.589,6.258 667.391,5.518 667.12,4.775 666.784,4.098 666.382,3.441 665.928,2.847 665.417,2.286 664.854,1.778 664.24,1.322 663.592,0.935 662.887,0.598 662.166,0.345 661.406,0.152 660.622,0.038 659.864,0z M7.247,390.96L6.562,390.863 5.894,390.693 5.267,390.474 4.652,390.179 4.086,389.843 3.549,389.443 3.059,389.007 2.606,388.517 2.207,387.997 1.855,387.421 1.561,386.834 1.326,386.185 1.152,385.537 1.041,384.847 1.001,384.121 1,7.917 1.032,7.246 1.131,6.561 1.301,5.894 1.519,5.267 1.815,4.651 2.15,4.085 2.549,3.551 2.994,3.056 3.483,2.606 4.002,2.207 4.579,1.854 5.167,1.561 5.816,1.325 6.462,1.151 7.152,1.041 7.88,1.001 659.839,0.999 660.523,1.032 661.208,1.131 661.874,1.301 662.503,1.519 663.117,1.814 663.683,2.15 664.218,2.549 664.71,2.992 665.159,3.485 665.556,4.003 665.908,4.578 666.202,5.166 666.437,5.816 666.611,6.462 666.721,7.151 666.762,7.879 666.763,384.07 666.731,384.754 666.631,385.439 666.462,386.105 666.243,386.734 665.948,387.347 665.612,387.913 665.212,388.451 664.779,388.939 664.285,389.39 663.766,389.786 663.19,390.138 662.602,390.433 661.954,390.668 661.307,390.841 660.617,390.953 659.89,390.993 7.93,390.993z" Height="725" Canvas.Left="-1.003" Canvas.Top="7.422" Width="406" Stretch="Fill">
                        <Path.Fill>
                            <LinearGradientBrush EndPoint="-0.021,0.083" StartPoint="0.997,0.897">
                                <GradientStop Color="#FFFF9FA1" Offset="0"/>
                                <GradientStop Color="#FF00AAF6" Offset="0.88"/>
                                <GradientStop Color="#FF00AAF6" Offset="1"/>
                            </LinearGradientBrush>
                        </Path.Fill>
                    </Path>
                    <Path Data="M0,0L3.54,0 3.54,351.862 0,351.862z" Fill="#FFABD9FF" Height="690.966" Canvas.Left="4.563" Opacity="0.659" Canvas.Top="20.017" Width="3.54" Stretch="Fill"/>
                    <Path Data="M0,0L3.441,0 3.441,351.763 0,351.763z" Fill="#FFABD9FF" Height="690.966" Canvas.Left="396.897" Opacity="0.659" Canvas.Top="20.017" Width="3.54" Stretch="Fill"/>
                    <Path Data="M5.739,0L58.329,0 65.285,6.686 0,6.686z" Fill="#FF71D3FF" Height="6.686" Canvas.Left="22" Canvas.Top="1.157" Width="65.285"/>
                    <Path Data="F1M0,8L0,0 8,0" Fill="White" Height="8" Canvas.Left="3.667" Canvas.Top="11" Width="8"/>
                    <Path Data="F1M0,0L8,0 8,8" Fill="White" Height="8" Canvas.Left="394.333" Canvas.Top="11" Width="8"/>
                    <Path Data="F1M8,0L8,8 0,8" Fill="White" Height="8" Canvas.Left="392" Canvas.Top="712.333" Width="8"/>
                    <Path Data="F1M8,8L0,8 0,0" Fill="White" Height="8" Canvas.Left="5" Canvas.Top="712.333" Width="8"/>
                    <Path Data="F1M12,0C5.4,0,0,5.4,0,12.001L0,41.001 635,41.001 635,12.001C635,5.4,629.6,0,623,0z" Height="41.001" Canvas.Left="12.004" Canvas.Top="14" Width="381.992" Stretch="Fill">
                        <Path.Fill>
                            <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                                <GradientStop Color="#FF9F8ADB" Offset="0"/>
                                <GradientStop Color="#FF0F5ED2" Offset="1"/>
                            </LinearGradientBrush>
                        </Path.Fill>
                        <Path.OpacityMask>
                            <LinearGradientBrush EndPoint="0.5,1" StartPoint="0.5,0">
                                <GradientStop Color="#9E000000" Offset="0"/>
                                <GradientStop Color="#E0000000" Offset="1"/>
                            </LinearGradientBrush>
                        </Path.OpacityMask>
                    </Path>
                    <!--<Label  Name="headerText" Content="今日值班" FontFamily="微软雅黑" FontSize="28" Foreground="#C1ECFF" FontWeight="Bold" Canvas.Left="140" Canvas.Top="5"/>-->
                </Canvas>

                <Grid Canvas.Left="10" Canvas.Top="44" Width="373">
                    <Grid.RowDefinitions>
                        <RowDefinition Height="Auto"></RowDefinition>
                        <RowDefinition Height="Auto"></RowDefinition>
                        <RowDefinition Height="Auto"></RowDefinition>
                    </Grid.RowDefinitions>
                    <Grid Grid.Row="0"  Background="#663F69" Opacity="1" Height="40" Margin="0,5,0,75" >
                    </Grid>
                    <TextBlock Text="株洲市市局值班人员" HorizontalAlignment="Center" Foreground="#FF9F9F"  VerticalAlignment="Center" FontSize="20" FontFamily="微软雅黑" FontWeight="Bold" Margin="91,11,102,83"></TextBlock>

                    <Grid Name="gridHeader"      Opacity="1"  Height="75" Margin="0,46,0,516" Grid.RowSpan="3">

                        <Grid.ColumnDefinitions>
                            <ColumnDefinition Width="1*"></ColumnDefinition>
                            <ColumnDefinition Width="1*"></ColumnDefinition>
                            <ColumnDefinition Width="1*"></ColumnDefinition>
                        </Grid.ColumnDefinitions>
                        <Border></Border>
                        <Border Grid.Column="0"></Border>
                        <Border Grid.Column="1"></Border>
                        <Border Grid.Column="2"></Border>
                        <Grid  Grid.Column="0" Height="75" Background="#351E43" >
                            <StackPanel  Height="55" VerticalAlignment="Center" >
                                <TextBlock Text="值班领导" Height="30" HorizontalAlignment="Center" FontSize="23" Foreground="#FF8B9E"></TextBlock>
                                <TextBlock Text="" Name="leader" Height="30" HorizontalAlignment="Center" FontSize="18" Foreground="#FFFFFF"></TextBlock>
                            </StackPanel>
                        </Grid>
                        <Grid  Grid.Column="1" Height="75"  Margin="3,0,0,0" Background="#351E43">
                            <StackPanel Height="55" VerticalAlignment="Center"   >
                                <TextBlock Text="值班主任" Height="30" HorizontalAlignment="Center" FontSize="23" Foreground="#FF8B9E"></TextBlock>
                                <TextBlock Text="" Name="director" Height="30" HorizontalAlignment="Center" FontSize="18" Foreground="#FFFFFF"></TextBlock>
                            </StackPanel>
                        </Grid>
                        <Grid  Grid.Column="2" Height="75" Margin="3,0,0,0" Background="#351E43" >
                            <StackPanel Height="55" VerticalAlignment="Center"  >
                                <TextBlock Text="值班长" Height="30" HorizontalAlignment="Center" FontSize="23" Foreground="#FF8B9E"></TextBlock>
                                <TextBlock Text=""  Name="foreman" Height="30" HorizontalAlignment="Center" FontSize="18" Foreground="#FFFFFF"></TextBlock>
                            </StackPanel>
                        </Grid>
                    </Grid>
                    <Grid Name="gridInfo" Grid.Row="2">
                        <Grid.RowDefinitions>
                            <RowDefinition Height="Auto"/>
                            <RowDefinition Height="Auto"/>
                            <RowDefinition Height="Auto"/>
                            <RowDefinition Height="Auto"/>
                            <RowDefinition Height="Auto"/>
                            <RowDefinition Height="Auto"/>
                            <RowDefinition Height="Auto"/>
                            <RowDefinition Height="Auto"/>
                            <RowDefinition Height="Auto"/>
                            <RowDefinition Height="Auto"/>
                            <RowDefinition Height="Auto"/>
                            <RowDefinition Height="Auto"/>
                        </Grid.RowDefinitions>
                        <Grid Name="grid1"  Height="45" ShowGridLines="False"    Opacity="1"  Grid.Row="0" Margin="0,10,0,0">

                            <Grid  Margin="0,0,2,0" Background="#53CAFF" Opacity="0.63" >
                            </Grid>
                            <TextBlock DockPanel.Dock="Left" Width="auto" Text="分局、县局值班人员" Name="header"   HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="22" FontWeight="Bold"  Foreground="#9BE5FF"></TextBlock>


                        </Grid>
                        <Grid Name="grid2"  Height="41"  Opacity="1" Grid.Row="1" Margin="0,2,0,0">

                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="3*"/>
                                <ColumnDefinition Width="4*"/>
                            </Grid.ColumnDefinitions>
                            <Grid Grid.Column="0" Margin="0,0,2,0" Background="#1D3E60" Opacity="1">
                            </Grid>
                            <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="policeStation1" Margin="25,0,0,0"  HorizontalAlignment="Left" VerticalAlignment="Center" FontSize="16" Foreground="#00F2F2"></TextBlock>

                            <Grid Grid.Column="1" Margin="0,0,2,0" Background="#1D3E60" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="name1" HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="16" Foreground="#C4EEFC"></TextBlock>
                            </Grid>

                        </Grid>
                        <Grid Name="grid3"  Height="41"  Opacity="1" Grid.Row="2" Margin="0,2,0,0">

                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="3*"/>
                                <ColumnDefinition Width="4*"/>
                            </Grid.ColumnDefinitions>
                            <Grid Grid.Column="0" Margin="0,0,2,0" Background="#0B2741" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="policeStation2"  Margin="25,0,0,0"  HorizontalAlignment="Left" VerticalAlignment="Center" FontSize="16" Foreground="#00F2F2"></TextBlock>
                            </Grid>
                            <Grid Grid.Column="1" Margin="0,0,2,0" Background="#0B2741" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="name2" HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="16" Foreground="#C4EEFC"></TextBlock>
                            </Grid>
                        </Grid>
                        <Grid Name="grid4"  Height="41"  Opacity="1" Grid.Row="3" Margin="0,2,0,0">

                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="3*"/>
                                <ColumnDefinition Width="4*"/>
                            </Grid.ColumnDefinitions>
                            <Grid Grid.Column="0" Margin="0,0,2,0" Background="#1D3E60" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="policeStation3"  Margin="25,0,0,0"  HorizontalAlignment="Left" VerticalAlignment="Center" FontSize="16" Foreground="#00F2F2"></TextBlock>
                            </Grid>
                            <Grid Grid.Column="1" Margin="0,0,2,0" Background="#1D3E60" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="name3" HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="16" Foreground="#C4EEFC"></TextBlock>
                            </Grid>

                        </Grid>
                        <Grid Name="grid5"  Height="41"  Opacity="1" Grid.Row="4" Margin="0,2,0,0">

                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="3*"/>
                                <ColumnDefinition Width="4*"/>
                            </Grid.ColumnDefinitions>
                            <Grid Grid.Column="0" Margin="0,0,2,0" Background="#0B2741" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="policeStation4"  Margin="25,0,0,0"  HorizontalAlignment="Left" VerticalAlignment="Center" FontSize="16" Foreground="#00F2F2"></TextBlock>
                            </Grid>
                            <Grid Grid.Column="1" Margin="0,0,2,0" Background="#0B2741" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="name4" HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="16" Foreground="#C4EEFC"></TextBlock>
                            </Grid>
                        </Grid>
                        <Grid Name="grid6"  Height="41"  Opacity="1" Grid.Row="5" Margin="0,2,0,0">

                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="3*"/>
                                <ColumnDefinition Width="4*"/>
                            </Grid.ColumnDefinitions>
                            <Grid Grid.Column="0" Margin="0,0,2,0" Background="#1D3E60" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="policeStation5"  Margin="25,0,0,0"  HorizontalAlignment="Left" VerticalAlignment="Center" FontSize="16" Foreground="#00F2F2"></TextBlock>
                            </Grid>
                            <Grid Grid.Column="1" Margin="0,0,2,0" Background="#1D3E60" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="name5" HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="16" Foreground="#C4EEFC"></TextBlock>
                            </Grid>

                        </Grid>
                        <Grid Name="grid7"  Height="41"  Opacity="1" Grid.Row="6" Margin="0,2,0,0">

                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="3*"/>
                                <ColumnDefinition Width="4*"/>
                            </Grid.ColumnDefinitions>
                            <Grid Grid.Column="0" Margin="0,0,2,0" Background="#0B2741" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="policeStation6"  Margin="25,0,0,0"  HorizontalAlignment="Left" VerticalAlignment="Center" FontSize="16" Foreground="#00F2F2"></TextBlock>
                            </Grid>
                            <Grid Grid.Column="1" Margin="0,0,2,0" Background="#0B2741" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="name6" HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="16" Foreground="#C4EEFC"></TextBlock>
                            </Grid>
                        </Grid>
                        <Grid Name="grid8"  Height="41"  Opacity="1" Grid.Row="7" Margin="0,2,0,0">

                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="3*"/>
                                <ColumnDefinition Width="4*"/>
                            </Grid.ColumnDefinitions>
                            <Grid Grid.Column="0" Margin="0,0,2,0" Background="#1D3E60" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="policeStation7"  Margin="25,0,0,0"  HorizontalAlignment="Left" VerticalAlignment="Center" FontSize="16" Foreground="#00F2F2"></TextBlock>
                            </Grid>
                            <Grid Grid.Column="1" Margin="0,0,2,0" Background="#1D3E60" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="name7" HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="16" Foreground="#C4EEFC"></TextBlock>
                            </Grid>

                        </Grid>
                        <Grid Name="grid9"  Height="41"  Opacity="1" Grid.Row="8" Margin="0,2,0,0">

                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="3*"/>
                                <ColumnDefinition Width="4*"/>
                            </Grid.ColumnDefinitions>
                            <Grid Grid.Column="0" Margin="0,0,2,0" Background="#0B2741" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="policeStation8"  Margin="25,0,0,0"  HorizontalAlignment="Left" VerticalAlignment="Center" FontSize="16" Foreground="#00F2F2"></TextBlock>
                            </Grid>
                            <Grid Grid.Column="1" Margin="0,0,2,0" Background="#0B2741" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="name8" HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="16" Foreground="#C4EEFC"></TextBlock>
                            </Grid>
                        </Grid>
                        <Grid Name="grid10"  Height="41"  Opacity="1" Grid.Row="9" Margin="0,2,0,0">

                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="3*"/>
                                <ColumnDefinition Width="4*"/>
                            </Grid.ColumnDefinitions>
                            <Grid Grid.Column="0" Margin="0,0,2,0" Background="#1D3E60" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="policeStation9"  Margin="25,0,0,0"  HorizontalAlignment="Left" VerticalAlignment="Center" FontSize="16" Foreground="#00F2F2"></TextBlock>
                            </Grid>
                            <Grid Grid.Column="1" Margin="0,0,2,0" Background="#1D3E60" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="name9" HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="16" Foreground="#C4EEFC"></TextBlock>
                            </Grid>

                        </Grid>
                        <Grid Name="grid11"  Height="41"  Opacity="1" Grid.Row="10" Margin="0,2,0,0">

                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="3*"/>
                                <ColumnDefinition Width="4*"/>
                            </Grid.ColumnDefinitions>
                            <Grid Grid.Column="0" Margin="0,0,2,0" Background="#0B2741" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="policeStation10"  Margin="25,0,0,0"  HorizontalAlignment="Left" VerticalAlignment="Center" FontSize="16" Foreground="#00F2F2"></TextBlock>
                            </Grid>
                            <Grid Grid.Column="1" Margin="0,0,2,0" Background="#0B2741" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="name10" HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="16" Foreground="#C4EEFC"></TextBlock>
                            </Grid>
                        </Grid>
                        <Grid Name="grid12"  Height="41"  Opacity="1" Grid.Row="11" Margin="0,2,0,0">

                            <Grid.ColumnDefinitions>
                                <ColumnDefinition Width="3*"/>
                                <ColumnDefinition Width="4*"/>
                            </Grid.ColumnDefinitions>
                            <Grid Grid.Column="0" Margin="0,0,2,0" Background="#1D3E60" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="policeStation11"  Margin="25,0,0,0"  HorizontalAlignment="Left" VerticalAlignment="Center" FontSize="16" Foreground="#00F2F2"></TextBlock>
                            </Grid>
                            <Grid Grid.Column="1" Margin="0,0,2,0" Background="#1D3E60" Opacity="1">
                                <TextBlock DockPanel.Dock="Left" Width="auto" Text="" Name="name11" HorizontalAlignment="Center" VerticalAlignment="Center" FontSize="16" Foreground="#C4EEFC"></TextBlock>
                            </Grid>
                        </Grid>
                    </Grid>
                </Grid>
            </Canvas>
        </Viewbox>
        <Viewbox  Grid.Row="0"  Stretch="None" HorizontalAlignment="Center" Margin="-18,0,0,0">
            <TextBlock x:Name="headerText"  Text="今日值班" FontWeight="Bold" Foreground="#C1ECFF" FontSize="28" FontFamily="微软雅黑"  />
        </Viewbox>
    </Grid>
</UserControl>
