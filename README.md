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

# Server Metrics 2026-03-17 08:52:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 50809.8 (14h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 380575
telemt_connections_bad_total 3614
telemt_handshake_timeouts_total 11504
telemt_upstream_connect_attempt_total 13146
telemt_upstream_connect_success_total 12717
telemt_upstream_connect_fail_total 429
telemt_upstream_connect_attempts_per_request{bucket="1"} 13146
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6794
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5773
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 429
telemt_me_keepalive_timeout_total 100
telemt_me_reconnect_attempts_total 9413
telemt_me_reconnect_success_total 7897
telemt_me_reader_eof_total 8398
telemt_me_idle_close_by_peer_total 8397
telemt_me_route_drop_no_conn_total 119226
telemt_me_route_drop_channel_closed_total 29
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 342136
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2649
telemt_desync_full_logged_total 740
telemt_desync_suppressed_total 1909
telemt_desync_frames_bucket_total{bucket="1_2"} 617
telemt_desync_frames_bucket_total{bucket="3_10"} 1239
telemt_desync_frames_bucket_total{bucket="gt_10"} 793
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8056
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 7875
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 344142
telemt_user_connections_current{user="hello"} 803
telemt_user_octets_from_client{user="hello"} 4825018931 (4.49 GB)
telemt_user_octets_to_client{user="hello"} 138422188111 (128.92 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 51061.5 (14h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 206662
telemt_connections_bad_total 2373
telemt_handshake_timeouts_total 12339
telemt_upstream_connect_attempt_total 13795
telemt_upstream_connect_success_total 13614
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 13795
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 127
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_reconnect_attempts_total 14391
telemt_me_reconnect_success_total 11092
telemt_me_reader_eof_total 11755
telemt_me_idle_close_by_peer_total 11755
telemt_me_route_drop_no_conn_total 75202
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181731
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 480
telemt_desync_full_logged_total 173
telemt_desync_suppressed_total 307
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 208
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 11306
telemt_me_refill_failed_total 102
telemt_me_writer_restored_same_endpoint_total 11076
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 181738
telemt_user_connections_current{user="hello"} 481
telemt_user_octets_from_client{user="hello"} 2209325360 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 73518868024 (68.47 GB)
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 66
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 50837.3 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127116
telemt_connections_bad_total 7565
telemt_handshake_timeouts_total 7353
telemt_upstream_connect_attempt_total 13475
telemt_upstream_connect_success_total 13405
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13475
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7413
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 11806
telemt_me_reconnect_success_total 10844
telemt_me_reader_eof_total 11612
telemt_me_idle_close_by_peer_total 11612
telemt_me_route_drop_no_conn_total 39297
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103193
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 269
telemt_desync_full_logged_total 70
telemt_desync_suppressed_total 199
telemt_desync_frames_bucket_total{bucket="1_2"} 98
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 63
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 11015
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 10833
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 103122
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 6635393484 (6.18 GB)
telemt_user_octets_to_client{user="hello"} 32729828676 (30.48 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 50896.6 (14h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275764
telemt_connections_bad_total 6177
telemt_handshake_timeouts_total 10609
telemt_upstream_connect_attempt_total 11673
telemt_upstream_connect_success_total 11567
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 11673
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5464
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6030
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 65
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 10041
telemt_me_reconnect_success_total 8968
telemt_me_reader_eof_total 9541
telemt_me_idle_close_by_peer_total 9541
telemt_me_route_drop_no_conn_total 74731
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 217070
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 458
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 287
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 198
telemt_desync_frames_bucket_total{bucket="gt_10"} 143
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 9140
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 8960
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 172
telemt_user_connections_total{user="hello"} 217059
telemt_user_connections_current{user="hello"} 571
telemt_user_octets_from_client{user="hello"} 2299256582 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 92231696281 (85.90 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 171
telemt_user_unique_ips_recent_window{user="hello"} 86
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 50868.5 (14h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 156334
telemt_connections_bad_total 42075
telemt_handshake_timeouts_total 2709
telemt_upstream_connect_attempt_total 15555
telemt_upstream_connect_success_total 15348
telemt_upstream_connect_fail_total 207
telemt_upstream_connect_attempts_per_request{bucket="1"} 15555
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6860
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8294
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 194
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 207
telemt_me_reconnect_attempts_total 19801
telemt_me_reconnect_success_total 12693
telemt_me_reader_eof_total 13476
telemt_me_idle_close_by_peer_total 13476
telemt_me_route_drop_no_conn_total 41009
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 106684
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 310
telemt_desync_full_logged_total 77
telemt_desync_suppressed_total 233
telemt_desync_frames_bucket_total{bucket="1_2"} 146
telemt_desync_frames_bucket_total{bucket="3_10"} 108
telemt_desync_frames_bucket_total{bucket="gt_10"} 56
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 13072
telemt_me_refill_failed_total 220
telemt_me_writer_restored_same_endpoint_total 12685
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 379
telemt_user_connections_total{user="hello"} 106715
telemt_user_connections_current{user="hello"} 257
telemt_user_octets_from_client{user="hello"} 1706277555 (1.59 GB)
telemt_user_octets_to_client{user="hello"} 49034477658 (45.67 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 92
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 51029.7 (14h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375085
telemt_connections_bad_total 46359
telemt_handshake_timeouts_total 3796
telemt_upstream_connect_attempt_total 10491
telemt_upstream_connect_success_total 10434
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 10491
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5106
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5312
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 11776
telemt_me_reconnect_success_total 7898
telemt_me_reader_eof_total 8531
telemt_me_idle_close_by_peer_total 8531
telemt_me_route_drop_no_conn_total 258881
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 381711
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 473
telemt_desync_full_logged_total 194
telemt_desync_suppressed_total 279
telemt_desync_frames_bucket_total{bucket="1_2"} 144
telemt_desync_frames_bucket_total{bucket="3_10"} 170
telemt_desync_frames_bucket_total{bucket="gt_10"} 159
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 8135
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 7884
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 237
telemt_user_connections_total{user="hello"} 303613
telemt_user_connections_current{user="hello"} 891
telemt_user_octets_from_client{user="hello"} 4220698064 (3.93 GB)
telemt_user_octets_to_client{user="hello"} 175353208416 (163.31 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 39036.0 (10h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3761
telemt_connections_bad_total 209
telemt_handshake_timeouts_total 7
telemt_upstream_connect_attempt_total 19116
telemt_upstream_connect_success_total 19103
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 19116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_reconnect_attempts_total 17178
telemt_me_reconnect_success_total 17052
telemt_me_reader_eof_total 18619
telemt_me_idle_close_by_peer_total 18619
telemt_me_route_drop_no_conn_total 734
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3491
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 17208
telemt_me_writer_restored_same_endpoint_total 17052
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 156
telemt_user_connections_total{user="hello"} 3491
telemt_user_connections_current{user="hello"} 71
telemt_user_octets_from_client{user="hello"} 727479948 (693.78 MB)
telemt_user_octets_to_client{user="hello"} 21711763908 (20.22 GB)
telemt_user_unique_ips_current{user="hello"} 13
telemt_user_unique_ips_recent_window{user="hello"} 8
```