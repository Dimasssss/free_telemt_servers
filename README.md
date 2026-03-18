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

# Server Metrics 2026-03-18 22:48:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 3624.9 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 44222
telemt_connections_bad_total 4179
telemt_connections_current 684
telemt_connections_me_current 684
telemt_handshake_timeouts_total 423
telemt_upstream_connect_attempt_total 622
telemt_upstream_connect_success_total 614
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 292
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 321
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 421
telemt_me_reconnect_success_total 420
telemt_me_reader_eof_total 406
telemt_me_idle_close_by_peer_total 406
telemt_me_route_drop_no_conn_total 16988
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 39992
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 166
telemt_desync_full_logged_total 63
telemt_desync_suppressed_total 103
telemt_desync_frames_bucket_total{bucket="1_2"} 36
telemt_desync_frames_bucket_total{bucket="3_10"} 60
telemt_desync_frames_bucket_total{bucket="gt_10"} 70
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 412
telemt_me_writer_restored_same_endpoint_total 410
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 37239
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 420417864 (400.94 MB)
telemt_user_octets_to_client{user="hello"} 16702446216 (15.56 GB)
telemt_user_unique_ips_current{user="hello"} 258
telemt_user_unique_ips_recent_window{user="hello"} 70
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 3628.6 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 105260
telemt_connections_bad_total 2851
telemt_connections_current 1818
telemt_connections_me_current 1818
telemt_handshake_timeouts_total 817
telemt_upstream_connect_attempt_total 566
telemt_upstream_connect_success_total 554
telemt_upstream_connect_fail_total 11
telemt_upstream_connect_attempts_per_request{bucket="1"} 565
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 272
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 11
telemt_me_reconnect_attempts_total 355
telemt_me_reconnect_success_total 353
telemt_me_reader_eof_total 354
telemt_me_idle_close_by_peer_total 354
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 37568
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96029
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 341
telemt_desync_full_logged_total 117
telemt_desync_suppressed_total 224
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 158
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 365
telemt_me_writer_restored_same_endpoint_total 343
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 96072
telemt_user_connections_current{user="hello"} 1818
telemt_user_octets_from_client{user="hello"} 5556907232 (5.18 GB)
telemt_user_octets_to_client{user="hello"} 40507111016 (37.73 GB)
telemt_user_unique_ips_current{user="hello"} 667
telemt_user_unique_ips_recent_window{user="hello"} 175
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 3625.9 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 88683
telemt_connections_bad_total 12581
telemt_connections_current 1331
telemt_connections_me_current 1331
telemt_handshake_timeouts_total 2356
telemt_upstream_connect_attempt_total 680
telemt_upstream_connect_success_total 680
telemt_upstream_connect_attempts_per_request{bucket="1"} 680
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 363
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 317
telemt_me_reconnect_attempts_total 478
telemt_me_reconnect_success_total 478
telemt_me_reader_eof_total 471
telemt_me_idle_close_by_peer_total 471
telemt_me_route_drop_no_conn_total 31165
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71235
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 288
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 175
telemt_desync_frames_bucket_total{bucket="1_2"} 50
telemt_desync_frames_bucket_total{bucket="3_10"} 122
telemt_desync_frames_bucket_total{bucket="gt_10"} 116
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 480
telemt_me_writer_restored_same_endpoint_total 462
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 71239
telemt_user_connections_current{user="hello"} 1331
telemt_user_octets_from_client{user="hello"} 883708892 (842.77 MB)
telemt_user_octets_to_client{user="hello"} 46009322056 (42.85 GB)
telemt_user_unique_ips_current{user="hello"} 563
telemt_user_unique_ips_recent_window{user="hello"} 115
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 3679.1 (1h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 100694
telemt_connections_bad_total 16808
telemt_connections_current 1098
telemt_connections_me_current 1098
telemt_handshake_timeouts_total 1989
telemt_upstream_connect_attempt_total 634
telemt_upstream_connect_success_total 634
telemt_upstream_connect_attempts_per_request{bucket="1"} 634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 342
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 290
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 410
telemt_me_reconnect_success_total 408
telemt_me_reader_eof_total 406
telemt_me_idle_close_by_peer_total 406
telemt_me_route_drop_no_conn_total 45190
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 77377
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 165
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 106
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 66
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 415
telemt_me_writer_restored_same_endpoint_total 384
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 7
telemt_user_connections_total{user="hello"} 77307
telemt_user_connections_current{user="hello"} 1098
telemt_user_octets_from_client{user="hello"} 840031484 (801.12 MB)
telemt_user_octets_to_client{user="hello"} 28424494892 (26.47 GB)
telemt_user_unique_ips_current{user="hello"} 474
telemt_user_unique_ips_recent_window{user="hello"} 126
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 3622.7 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 93848
telemt_connections_bad_total 4048
telemt_connections_current 1435
telemt_connections_me_current 1435
telemt_handshake_timeouts_total 2886
telemt_upstream_connect_attempt_total 616
telemt_upstream_connect_success_total 610
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 616
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 298
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 410
telemt_me_reconnect_success_total 408
telemt_me_reader_eof_total 398
telemt_me_idle_close_by_peer_total 398
telemt_me_route_drop_no_conn_total 27737
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 74189
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 350
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 207
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 124
telemt_desync_frames_bucket_total{bucket="gt_10"} 132
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 406
telemt_me_writer_restored_same_endpoint_total 384
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_user_connections_total{user="hello"} 74153
telemt_user_connections_current{user="hello"} 1435
telemt_user_octets_from_client{user="hello"} 907009960 (864.99 MB)
telemt_user_octets_to_client{user="hello"} 45784143956 (42.64 GB)
telemt_user_unique_ips_current{user="hello"} 601
telemt_user_unique_ips_recent_window{user="hello"} 135
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 3634.0 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 21804
telemt_connections_bad_total 4999
telemt_connections_current 384
telemt_connections_me_current 384
telemt_handshake_timeouts_total 67
telemt_upstream_connect_attempt_total 966
telemt_upstream_connect_success_total 935
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 358
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_reconnect_attempts_total 1540
telemt_me_reconnect_success_total 738
telemt_me_reader_eof_total 730
telemt_me_idle_close_by_peer_total 730
telemt_me_route_drop_no_conn_total 6756
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16241
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
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
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 733
telemt_me_refill_failed_total 25
telemt_me_writer_restored_same_endpoint_total 708
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 16241
telemt_user_connections_current{user="hello"} 384
telemt_user_octets_from_client{user="hello"} 227276652 (216.75 MB)
telemt_user_octets_to_client{user="hello"} 9798192964 (9.13 GB)
telemt_user_unique_ips_current{user="hello"} 160
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 3625.0 (1h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73511
telemt_connections_bad_total 11160
telemt_connections_current 1266
telemt_connections_me_current 1266
telemt_handshake_timeouts_total 2076
telemt_upstream_connect_attempt_total 610
telemt_upstream_connect_success_total 610
telemt_upstream_connect_attempts_per_request{bucket="1"} 610
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 330
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 280
telemt_me_reconnect_attempts_total 407
telemt_me_reconnect_success_total 407
telemt_me_reader_eof_total 405
telemt_me_idle_close_by_peer_total 405
telemt_me_route_drop_no_conn_total 20798
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58620
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 494
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 313
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 193
telemt_desync_frames_bucket_total{bucket="gt_10"} 206
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 412
telemt_me_writer_restored_same_endpoint_total 392
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 58624
telemt_user_connections_current{user="hello"} 1266
telemt_user_octets_from_client{user="hello"} 677763180 (646.37 MB)
telemt_user_octets_to_client{user="hello"} 35886411340 (33.42 GB)
telemt_user_unique_ips_current{user="hello"} 528
telemt_user_unique_ips_recent_window{user="hello"} 113
```