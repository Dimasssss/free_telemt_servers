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

# Server Metrics 2026-03-18 22:33:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 2704.1 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32191
telemt_connections_bad_total 2610
telemt_connections_current 788
telemt_connections_me_current 788
telemt_handshake_timeouts_total 334
telemt_upstream_connect_attempt_total 449
telemt_upstream_connect_success_total 443
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 209
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 234
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 295
telemt_me_reconnect_success_total 294
telemt_me_reader_eof_total 268
telemt_me_idle_close_by_peer_total 268
telemt_me_route_drop_no_conn_total 13350
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30138
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 20
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 110
telemt_desync_full_logged_total 45
telemt_desync_suppressed_total 65
telemt_desync_frames_bucket_total{bucket="1_2"} 23
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 284
telemt_me_writer_restored_same_endpoint_total 284
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 136
telemt_user_connections_total{user="hello"} 27386
telemt_user_connections_current{user="hello"} 788
telemt_user_octets_from_client{user="hello"} 297119524 (283.36 MB)
telemt_user_octets_to_client{user="hello"} 13444018044 (12.52 GB)
telemt_user_unique_ips_current{user="hello"} 289
telemt_user_unique_ips_recent_window{user="hello"} 73
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 2708.0 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83089
telemt_connections_bad_total 2367
telemt_connections_current 1906
telemt_connections_me_current 1906
telemt_handshake_timeouts_total 651
telemt_upstream_connect_attempt_total 400
telemt_upstream_connect_success_total 393
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 400
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 201
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 190
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 240
telemt_me_reconnect_success_total 239
telemt_me_reader_eof_total 231
telemt_me_idle_close_by_peer_total 231
telemt_me_seq_mismatch_total 1
telemt_me_route_drop_no_conn_total 30703
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75853
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 238
telemt_desync_full_logged_total 83
telemt_desync_suppressed_total 155
telemt_desync_frames_bucket_total{bucket="1_2"} 47
telemt_desync_frames_bucket_total{bucket="3_10"} 79
telemt_desync_frames_bucket_total{bucket="gt_10"} 112
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 248
telemt_me_writer_restored_same_endpoint_total 229
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 9
telemt_user_connections_total{user="hello"} 75856
telemt_user_connections_current{user="hello"} 1906
telemt_user_octets_from_client{user="hello"} 3608783160 (3.36 GB)
telemt_user_octets_to_client{user="hello"} 29636426044 (27.60 GB)
telemt_user_unique_ips_current{user="hello"} 693
telemt_user_unique_ips_recent_window{user="hello"} 186
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 2704.8 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 70769
telemt_connections_bad_total 8866
telemt_connections_current 1486
telemt_connections_me_current 1486
telemt_handshake_timeouts_total 1852
telemt_upstream_connect_attempt_total 493
telemt_upstream_connect_success_total 493
telemt_upstream_connect_attempts_per_request{bucket="1"} 493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 278
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 215
telemt_me_reconnect_attempts_total 339
telemt_me_reconnect_success_total 339
telemt_me_reader_eof_total 325
telemt_me_idle_close_by_peer_total 325
telemt_me_route_drop_no_conn_total 24828
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 58119
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 213
telemt_desync_full_logged_total 85
telemt_desync_suppressed_total 128
telemt_desync_frames_bucket_total{bucket="1_2"} 34
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 87
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 339
telemt_me_writer_restored_same_endpoint_total 323
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_user_connections_total{user="hello"} 58126
telemt_user_connections_current{user="hello"} 1486
telemt_user_octets_from_client{user="hello"} 749240884 (714.53 MB)
telemt_user_octets_to_client{user="hello"} 37260939828 (34.70 GB)
telemt_user_unique_ips_current{user="hello"} 604
telemt_user_unique_ips_recent_window{user="hello"} 139
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 2758.1 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 73992
telemt_connections_bad_total 5842
telemt_connections_current 1268
telemt_connections_me_current 1268
telemt_handshake_timeouts_total 1042
telemt_upstream_connect_attempt_total 483
telemt_upstream_connect_success_total 483
telemt_upstream_connect_attempts_per_request{bucket="1"} 483
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 261
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 220
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 309
telemt_me_reconnect_success_total 307
telemt_me_reader_eof_total 296
telemt_me_idle_close_by_peer_total 296
telemt_me_route_drop_no_conn_total 38671
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 63594
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 139
telemt_desync_full_logged_total 51
telemt_desync_suppressed_total 88
telemt_desync_frames_bucket_total{bucket="1_2"} 27
telemt_desync_frames_bucket_total{bucket="3_10"} 59
telemt_desync_frames_bucket_total{bucket="gt_10"} 53
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 312
telemt_me_writer_restored_same_endpoint_total 283
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 268
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 63532
telemt_user_connections_current{user="hello"} 1268
telemt_user_octets_from_client{user="hello"} 747510236 (712.88 MB)
telemt_user_octets_to_client{user="hello"} 20775227652 (19.35 GB)
telemt_user_unique_ips_current{user="hello"} 512
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 2701.7 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 72906
telemt_connections_bad_total 3245
telemt_connections_current 1474
telemt_connections_me_current 1474
telemt_handshake_timeouts_total 2078
telemt_upstream_connect_attempt_total 453
telemt_upstream_connect_success_total 449
telemt_upstream_connect_fail_total 4
telemt_upstream_connect_attempts_per_request{bucket="1"} 453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 234
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 214
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4
telemt_me_reconnect_attempts_total 294
telemt_me_reconnect_success_total 292
telemt_me_reader_eof_total 273
telemt_me_idle_close_by_peer_total 273
telemt_me_route_drop_no_conn_total 21149
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57960
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 261
telemt_desync_full_logged_total 113
telemt_desync_suppressed_total 148
telemt_desync_frames_bucket_total{bucket="1_2"} 73
telemt_desync_frames_bucket_total{bucket="3_10"} 90
telemt_desync_frames_bucket_total{bucket="gt_10"} 98
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 288
telemt_me_writer_restored_same_endpoint_total 268
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_user_connections_total{user="hello"} 57924
telemt_user_connections_current{user="hello"} 1474
telemt_user_octets_from_client{user="hello"} 706945604 (674.20 MB)
telemt_user_octets_to_client{user="hello"} 35836231128 (33.38 GB)
telemt_user_unique_ips_current{user="hello"} 610
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 2712.9 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17049
telemt_connections_bad_total 4256
telemt_connections_current 398
telemt_connections_me_current 398
telemt_handshake_timeouts_total 64
telemt_upstream_connect_attempt_total 762
telemt_upstream_connect_success_total 742
telemt_upstream_connect_fail_total 20
telemt_upstream_connect_attempts_per_request{bucket="1"} 762
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 269
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 20
telemt_me_reconnect_attempts_total 1266
telemt_me_reconnect_success_total 592
telemt_me_reader_eof_total 559
telemt_me_idle_close_by_peer_total 559
telemt_me_route_drop_no_conn_total 5038
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 12333
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
telemt_me_writer_removed_unexpected_total 581
telemt_me_refill_failed_total 21
telemt_me_writer_restored_same_endpoint_total 562
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_user_connections_total{user="hello"} 12333
telemt_user_connections_current{user="hello"} 398
telemt_user_octets_from_client{user="hello"} 203379388 (193.96 MB)
telemt_user_octets_to_client{user="hello"} 7095536780 (6.61 GB)
telemt_user_unique_ips_current{user="hello"} 167
telemt_user_unique_ips_recent_window{user="hello"} 37
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 2703.8 (0h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58696
telemt_connections_bad_total 9934
telemt_connections_current 1391
telemt_connections_me_current 1391
telemt_handshake_timeouts_total 1587
telemt_upstream_connect_attempt_total 448
telemt_upstream_connect_success_total 448
telemt_upstream_connect_attempts_per_request{bucket="1"} 448
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 252
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 196
telemt_me_reconnect_attempts_total 293
telemt_me_reconnect_success_total 293
telemt_me_reader_eof_total 281
telemt_me_idle_close_by_peer_total 281
telemt_me_route_drop_no_conn_total 15525
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45716
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 400
telemt_desync_full_logged_total 145
telemt_desync_suppressed_total 255
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 153
telemt_desync_frames_bucket_total{bucket="gt_10"} 172
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 296
telemt_me_writer_restored_same_endpoint_total 278
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 3
telemt_user_connections_total{user="hello"} 45721
telemt_user_connections_current{user="hello"} 1391
telemt_user_octets_from_client{user="hello"} 572581372 (546.06 MB)
telemt_user_octets_to_client{user="hello"} 30377829896 (28.29 GB)
telemt_user_unique_ips_current{user="hello"} 562
telemt_user_unique_ips_recent_window{user="hello"} 133
```