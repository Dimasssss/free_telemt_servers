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

# Server Metrics 2026-03-17 07:35:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 46225.4 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 304670
telemt_connections_bad_total 3535
telemt_handshake_timeouts_total 9759
telemt_upstream_connect_attempt_total 9537
telemt_upstream_connect_success_total 9485
telemt_upstream_connect_fail_total 51
telemt_upstream_connect_attempts_per_request{bucket="1"} 9536
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4349
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5130
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 51
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7206
telemt_me_reconnect_success_total 7176
telemt_me_reader_eof_total 7642
telemt_me_idle_close_by_peer_total 7642
telemt_me_route_drop_no_conn_total 93013
telemt_me_route_drop_channel_closed_total 19
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 273577
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2079
telemt_desync_full_logged_total 607
telemt_desync_suppressed_total 1472
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 1045
telemt_desync_frames_bucket_total{bucket="gt_10"} 589
telemt_pool_swap_total 48
telemt_me_writer_removed_unexpected_total 7250
telemt_me_writer_restored_same_endpoint_total 7155
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 273349
telemt_user_connections_current{user="hello"} 817
telemt_user_octets_from_client{user="hello"} 3565059920 (3.32 GB)
telemt_user_octets_to_client{user="hello"} 118990763636 (110.82 GB)
telemt_user_unique_ips_current{user="hello"} 280
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 46477.0 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 172144
telemt_connections_bad_total 2349
telemt_handshake_timeouts_total 11874
telemt_upstream_connect_attempt_total 12727
telemt_upstream_connect_success_total 12563
telemt_upstream_connect_fail_total 164
telemt_upstream_connect_attempts_per_request{bucket="1"} 12727
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7128
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 164
telemt_me_reconnect_attempts_total 11445
telemt_me_reconnect_success_total 10262
telemt_me_reader_eof_total 10833
telemt_me_idle_close_by_peer_total 10833
telemt_me_route_drop_no_conn_total 62143
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 148886
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 382
telemt_desync_full_logged_total 137
telemt_desync_suppressed_total 245
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 175
telemt_desync_frames_bucket_total{bucket="gt_10"} 104
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 10394
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 10246
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 148920
telemt_user_connections_current{user="hello"} 452
telemt_user_octets_from_client{user="hello"} 1816364856 (1.69 GB)
telemt_user_octets_to_client{user="hello"} 61231484716 (57.03 GB)
telemt_user_unique_ips_current{user="hello"} 146
telemt_user_unique_ips_recent_window{user="hello"} 62
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 46253.6 (12h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103179
telemt_connections_bad_total 3565
telemt_handshake_timeouts_total 4466
telemt_upstream_connect_attempt_total 12142
telemt_upstream_connect_success_total 12079
telemt_upstream_connect_fail_total 63
telemt_upstream_connect_attempts_per_request{bucket="1"} 12142
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5337
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6680
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 63
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 9804
telemt_me_reconnect_success_total 9747
telemt_me_reader_eof_total 10438
telemt_me_idle_close_by_peer_total 10438
telemt_me_route_drop_no_conn_total 33089
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 86510
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 125
telemt_desync_full_logged_total 38
telemt_desync_suppressed_total 87
telemt_desync_frames_bucket_total{bucket="1_2"} 26
telemt_desync_frames_bucket_total{bucket="3_10"} 44
telemt_desync_frames_bucket_total{bucket="gt_10"} 55
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 9867
telemt_me_writer_restored_same_endpoint_total 9736
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 86466
telemt_user_connections_current{user="hello"} 289
telemt_user_octets_from_client{user="hello"} 6363070804 (5.93 GB)
telemt_user_octets_to_client{user="hello"} 26674911884 (24.84 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 46312.4 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 200888
telemt_connections_bad_total 6048
telemt_handshake_timeouts_total 9989
telemt_upstream_connect_attempt_total 10631
telemt_upstream_connect_success_total 10540
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 10631
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5487
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 60
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_keepalive_timeout_total 5
telemt_me_reconnect_attempts_total 8236
telemt_me_reconnect_success_total 8165
telemt_me_reader_eof_total 8667
telemt_me_idle_close_by_peer_total 8667
telemt_me_route_drop_no_conn_total 60381
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 169387
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 331
telemt_desync_full_logged_total 112
telemt_desync_suppressed_total 219
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 134
telemt_desync_frames_bucket_total{bucket="gt_10"} 120
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 8287
telemt_me_writer_restored_same_endpoint_total 8157
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 169394
telemt_user_connections_current{user="hello"} 554
telemt_user_octets_from_client{user="hello"} 1772093210 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 77094141857 (71.80 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 175
telemt_user_unique_ips_recent_window{user="hello"} 81
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 46284.4 (12h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132717
telemt_connections_bad_total 38532
telemt_handshake_timeouts_total 2444
telemt_upstream_connect_attempt_total 14080
telemt_upstream_connect_success_total 13896
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 14080
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6229
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 190
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_reconnect_attempts_total 14729
telemt_me_reconnect_success_total 11467
telemt_me_reader_eof_total 12110
telemt_me_idle_close_by_peer_total 12110
telemt_me_route_drop_no_conn_total 34559
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87967
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 92
telemt_desync_full_logged_total 32
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 28
telemt_desync_frames_bucket_total{bucket="gt_10"} 30
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 11712
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 11459
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 88008
telemt_user_connections_current{user="hello"} 193
telemt_user_octets_from_client{user="hello"} 920448755 (877.81 MB)
telemt_user_octets_to_client{user="hello"} 41518778922 (38.67 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 46445.7 (12h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314240
telemt_connections_bad_total 42166
telemt_handshake_timeouts_total 2756
telemt_upstream_connect_attempt_total 9612
telemt_upstream_connect_success_total 9562
telemt_upstream_connect_fail_total 50
telemt_upstream_connect_attempts_per_request{bucket="1"} 9612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4608
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4939
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 50
telemt_me_keepalive_timeout_total 16
telemt_me_reconnect_attempts_total 8500
telemt_me_reconnect_success_total 7249
telemt_me_reader_eof_total 7772
telemt_me_idle_close_by_peer_total 7772
telemt_me_route_drop_no_conn_total 237772
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 335214
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 358
telemt_desync_full_logged_total 160
telemt_desync_suppressed_total 198
telemt_desync_frames_bucket_total{bucket="1_2"} 123
telemt_desync_frames_bucket_total{bucket="3_10"} 129
telemt_desync_frames_bucket_total{bucket="gt_10"} 106
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 7393
telemt_me_refill_failed_total 38
telemt_me_writer_restored_same_endpoint_total 7235
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 257143
telemt_user_connections_current{user="hello"} 722
telemt_user_octets_from_client{user="hello"} 3670621716 (3.42 GB)
telemt_user_octets_to_client{user="hello"} 162875616228 (151.69 GB)
telemt_user_unique_ips_current{user="hello"} 243
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 34451.9 (9h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1628
telemt_connections_bad_total 194
telemt_handshake_timeouts_total 4
telemt_upstream_connect_attempt_total 17196
telemt_upstream_connect_success_total 17195
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 17196
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7423
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 15479
telemt_me_reconnect_success_total 15391
telemt_me_reader_eof_total 16850
telemt_me_idle_close_by_peer_total 16850
telemt_me_route_drop_no_conn_total 245
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1417
telemt_me_writer_pick_total{mode="p2c",result="full"} 3
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 15528
telemt_me_writer_restored_same_endpoint_total 15391
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 137
telemt_user_connections_total{user="hello"} 1417
telemt_user_connections_current{user="hello"} 16
telemt_user_octets_from_client{user="hello"} 217594024 (207.51 MB)
telemt_user_octets_to_client{user="hello"} 15501552572 (14.44 GB)
telemt_user_unique_ips_current{user="hello"} 8
telemt_user_unique_ips_recent_window{user="hello"} 1
```