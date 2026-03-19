# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-40
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s2.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## koara.io
- Локация: Германия, Франкфурт-на-Майне
- Тариф: DE-2
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 639 RUB
- Оплачен до: 25 марта
- Ссылка:
```bash
tg://proxy?server=s3.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## landvps.ru
- Локация: Финляндия
- Тариф: FL-2
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 200 Mbps/s
- Цена в месяц: 800 RUB
- Оплачен до: 26 марта
- Ссылка:
```bash
tg://proxy?server=s4.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## rdp-onedash.ru
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Оплачен до: 14 апреля
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Нидерланды, Амстердам
- Тариф: Burstable
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 10 Gbit/s
- Цена в месяц: €7.98
- Оплачен до: 13 апреля
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-19 00:15:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 8842.5 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 102792
telemt_connections_bad_total 11444
telemt_connections_current 662
telemt_connections_me_current 662
telemt_handshake_timeouts_total 1082
telemt_upstream_connect_attempt_total 1715
telemt_upstream_connect_success_total 1688
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 1715
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 779
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1238
telemt_me_reconnect_success_total 1235
telemt_me_reader_eof_total 1261
telemt_me_idle_close_by_peer_total 1261
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 32730
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 85652
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 475
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 330
telemt_desync_frames_bucket_total{bucket="1_2"} 145
telemt_desync_frames_bucket_total{bucket="3_10"} 207
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1234
telemt_me_writer_restored_same_endpoint_total 1223
telemt_me_writer_restored_fallback_total 12
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 82887
telemt_user_connections_current{user="hello"} 662
telemt_user_octets_from_client{user="hello"} 772562232 (736.77 MB)
telemt_user_octets_to_client{user="hello"} 32632873668 (30.39 GB)
telemt_user_unique_ips_current{user="hello"} 272
telemt_user_unique_ips_recent_window{user="hello"} 88
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 8846.2 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220834
telemt_connections_bad_total 16846
telemt_connections_current 1581
telemt_connections_me_current 1581
telemt_handshake_timeouts_total 1986
telemt_upstream_connect_attempt_total 1666
telemt_upstream_connect_success_total 1628
telemt_upstream_connect_fail_total 38
telemt_upstream_connect_attempts_per_request{bucket="1"} 1666
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 38
telemt_me_reconnect_attempts_total 1172
telemt_me_reconnect_success_total 1171
telemt_me_reader_eof_total 1220
telemt_me_idle_close_by_peer_total 1220
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 67844
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189656
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 773
telemt_desync_full_logged_total 256
telemt_desync_suppressed_total 517
telemt_desync_frames_bucket_total{bucket="1_2"} 177
telemt_desync_frames_bucket_total{bucket="3_10"} 262
telemt_desync_frames_bucket_total{bucket="gt_10"} 334
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1191
telemt_me_writer_restored_same_endpoint_total 1160
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 189729
telemt_user_connections_current{user="hello"} 1581
telemt_user_octets_from_client{user="hello"} 10550089912 (9.83 GB)
telemt_user_octets_to_client{user="hello"} 71128602148 (66.24 GB)
telemt_user_unique_ips_current{user="hello"} 628
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 8843.4 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172611
telemt_connections_bad_total 26661
telemt_connections_current 1186
telemt_connections_me_current 1186
telemt_handshake_timeouts_total 4650
telemt_upstream_connect_attempt_total 1706
telemt_upstream_connect_success_total 1706
telemt_upstream_connect_attempts_per_request{bucket="1"} 1706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 855
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 847
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1250
telemt_me_reconnect_success_total 1247
telemt_me_reader_eof_total 1296
telemt_me_idle_close_by_peer_total 1296
telemt_me_route_drop_no_conn_total 57632
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 136101
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 596
telemt_desync_full_logged_total 232
telemt_desync_suppressed_total 364
telemt_desync_frames_bucket_total{bucket="1_2"} 110
telemt_desync_frames_bucket_total{bucket="3_10"} 245
telemt_desync_frames_bucket_total{bucket="gt_10"} 241
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1264
telemt_me_writer_restored_same_endpoint_total 1231
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 136103
telemt_user_connections_current{user="hello"} 1186
telemt_user_octets_from_client{user="hello"} 1841122400 (1.71 GB)
telemt_user_octets_to_client{user="hello"} 80660096956 (75.12 GB)
telemt_user_unique_ips_current{user="hello"} 488
telemt_user_unique_ips_recent_window{user="hello"} 99
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 8896.7 (2h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182823
telemt_connections_bad_total 25378
telemt_connections_current 1017
telemt_connections_me_current 1017
telemt_handshake_timeouts_total 3398
telemt_upstream_connect_attempt_total 1629
telemt_upstream_connect_success_total 1629
telemt_upstream_connect_attempts_per_request{bucket="1"} 1629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 777
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 1175
telemt_me_reconnect_success_total 1170
telemt_me_reader_eof_total 1212
telemt_me_idle_close_by_peer_total 1212
telemt_me_route_drop_no_conn_total 68047
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 140827
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 366
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 231
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 151
telemt_desync_frames_bucket_total{bucket="gt_10"} 151
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1184
telemt_me_writer_restored_same_endpoint_total 1146
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 140753
telemt_user_connections_current{user="hello"} 1017
telemt_user_octets_from_client{user="hello"} 1546254952 (1.44 GB)
telemt_user_octets_to_client{user="hello"} 51922631148 (48.36 GB)
telemt_user_unique_ips_current{user="hello"} 412
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 8840.0 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188825
telemt_connections_bad_total 8286
telemt_connections_current 1174
telemt_connections_me_current 1174
telemt_handshake_timeouts_total 6702
telemt_upstream_connect_attempt_total 1630
telemt_upstream_connect_success_total 1619
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 1630
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 791
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 823
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 1163
telemt_me_reconnect_success_total 1157
telemt_me_reader_eof_total 1196
telemt_me_idle_close_by_peer_total 1196
telemt_me_route_drop_no_conn_total 61415
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 147225
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 603
telemt_desync_full_logged_total 244
telemt_desync_suppressed_total 359
telemt_desync_frames_bucket_total{bucket="1_2"} 143
telemt_desync_frames_bucket_total{bucket="3_10"} 210
telemt_desync_frames_bucket_total{bucket="gt_10"} 250
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1161
telemt_me_writer_restored_same_endpoint_total 1133
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 147155
telemt_user_connections_current{user="hello"} 1174
telemt_user_octets_from_client{user="hello"} 1971382084 (1.84 GB)
telemt_user_octets_to_client{user="hello"} 92972602592 (86.59 GB)
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 8851.7 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 47074
telemt_connections_bad_total 8236
telemt_connections_current 378
telemt_connections_me_current 378
telemt_handshake_timeouts_total 132
telemt_upstream_connect_attempt_total 2663
telemt_upstream_connect_success_total 2584
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 2663
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1275
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1309
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_reconnect_attempts_total 3957
telemt_me_reconnect_success_total 2131
telemt_me_reader_eof_total 2209
telemt_me_idle_close_by_peer_total 2209
telemt_me_route_drop_no_conn_total 17081
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 37604
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 24
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 18
telemt_desync_frames_bucket_total{bucket="1_2"} 13
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 2168
telemt_me_refill_failed_total 57
telemt_me_writer_restored_same_endpoint_total 2101
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 37605
telemt_user_connections_current{user="hello"} 378
telemt_user_octets_from_client{user="hello"} 436015764 (415.82 MB)
telemt_user_octets_to_client{user="hello"} 25747581268 (23.98 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 8842.4 (2h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 139548
telemt_connections_bad_total 17853
telemt_connections_current 1074
telemt_connections_me_current 1074
telemt_handshake_timeouts_total 5095
telemt_upstream_connect_attempt_total 1781
telemt_upstream_connect_success_total 1781
telemt_upstream_connect_attempts_per_request{bucket="1"} 1781
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 852
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 1325
telemt_me_reconnect_success_total 1321
telemt_me_reader_eof_total 1373
telemt_me_idle_close_by_peer_total 1373
telemt_me_route_drop_no_conn_total 41853
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 113970
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 780
telemt_desync_full_logged_total 307
telemt_desync_suppressed_total 473
telemt_desync_frames_bucket_total{bucket="1_2"} 127
telemt_desync_frames_bucket_total{bucket="3_10"} 328
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1337
telemt_me_writer_restored_same_endpoint_total 1306
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 113995
telemt_user_connections_current{user="hello"} 1074
telemt_user_octets_from_client{user="hello"} 1103285036 (1.03 GB)
telemt_user_octets_to_client{user="hello"} 60975410852 (56.79 GB)
telemt_user_unique_ips_current{user="hello"} 458
telemt_user_unique_ips_recent_window{user="hello"} 116
```