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

# Server Metrics 2026-03-16 19:34:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 2924.1 (0h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23242
telemt_connections_bad_total 214
telemt_handshake_timeouts_total 1295
telemt_upstream_connect_attempt_total 551
telemt_upstream_connect_success_total 544
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 551
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 256
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_reconnect_attempts_total 347
telemt_me_reconnect_success_total 346
telemt_me_reader_eof_total 329
telemt_me_idle_close_by_peer_total 329
telemt_me_route_drop_no_conn_total 6967
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 20725
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 104
telemt_desync_full_logged_total 22
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 53
telemt_desync_frames_bucket_total{bucket="3_10"} 27
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 338
telemt_me_writer_restored_same_endpoint_total 325
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 46
telemt_user_connections_total{user="hello"} 20718
telemt_user_connections_current{user="hello"} 586
telemt_user_octets_from_client{user="hello"} 382683328 (364.96 MB)
telemt_user_octets_to_client{user="hello"} 15561466888 (14.49 GB)
telemt_user_unique_ips_current{user="hello"} 192
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 3176.1 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19617
telemt_connections_bad_total 11
telemt_handshake_timeouts_total 743
telemt_upstream_connect_attempt_total 619
telemt_upstream_connect_success_total 611
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 268
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 297
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 415
telemt_me_reconnect_success_total 415
telemt_me_reader_eof_total 406
telemt_me_idle_close_by_peer_total 406
telemt_me_route_drop_no_conn_total 8295
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17801
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 61
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 43
telemt_desync_frames_bucket_total{bucket="1_2"} 15
telemt_desync_frames_bucket_total{bucket="3_10"} 25
telemt_desync_frames_bucket_total{bucket="gt_10"} 21
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 419
telemt_me_writer_restored_same_endpoint_total 399
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 17800
telemt_user_connections_current{user="hello"} 319
telemt_user_octets_from_client{user="hello"} 238711384 (227.65 MB)
telemt_user_octets_to_client{user="hello"} 6579860548 (6.13 GB)
telemt_user_unique_ips_current{user="hello"} 108
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 2951.7 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10090
telemt_connections_bad_total 47
telemt_handshake_timeouts_total 103
telemt_upstream_connect_attempt_total 618
telemt_upstream_connect_success_total 616
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 281
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 331
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_reconnect_attempts_total 419
telemt_me_reconnect_success_total 417
telemt_me_reader_eof_total 414
telemt_me_idle_close_by_peer_total 414
telemt_me_route_drop_no_conn_total 3053
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9696
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3
telemt_desync_full_logged_total 1
telemt_desync_suppressed_total 2
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="gt_10"} 1
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 415
telemt_me_writer_restored_same_endpoint_total 406
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_user_connections_total{user="hello"} 9695
telemt_user_connections_current{user="hello"} 210
telemt_user_octets_from_client{user="hello"} 344958720 (328.98 MB)
telemt_user_octets_to_client{user="hello"} 4700163236 (4.38 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 3010.9 (0h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20021
telemt_connections_bad_total 29
telemt_handshake_timeouts_total 276
telemt_upstream_connect_attempt_total 577
telemt_upstream_connect_success_total 565
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 577
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 299
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 262
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 366
telemt_me_reconnect_success_total 363
telemt_me_reader_eof_total 346
telemt_me_idle_close_by_peer_total 346
telemt_me_route_drop_no_conn_total 6229
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18950
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 50
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 37
telemt_desync_frames_bucket_total{bucket="1_2"} 11
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 363
telemt_me_writer_restored_same_endpoint_total 356
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 270
telemt_user_connections_total{user="hello"} 18946
telemt_user_connections_current{user="hello"} 287
telemt_user_octets_from_client{user="hello"} 289693764 (276.27 MB)
telemt_user_octets_to_client{user="hello"} 6759696388 (6.30 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 2982.9 (0h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 12068
telemt_connections_bad_total 3411
telemt_handshake_timeouts_total 50
telemt_upstream_connect_attempt_total 863
telemt_upstream_connect_success_total 851
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 863
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 427
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 26
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 656
telemt_me_reconnect_success_total 654
telemt_me_reader_eof_total 620
telemt_me_idle_close_by_peer_total 620
telemt_me_route_drop_no_conn_total 3241
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8254
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9
telemt_desync_full_logged_total 3
telemt_desync_suppressed_total 6
telemt_desync_frames_bucket_total{bucket="3_10"} 4
telemt_desync_frames_bucket_total{bucket="gt_10"} 5
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 638
telemt_me_writer_restored_same_endpoint_total 646
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_user_connections_total{user="hello"} 8252
telemt_user_connections_current{user="hello"} 209
telemt_user_octets_from_client{user="hello"} 59817792 (57.05 MB)
telemt_user_octets_to_client{user="hello"} 2741620216 (2.55 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 3144.0 (0h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 32888
telemt_connections_bad_total 42
telemt_handshake_timeouts_total 587
telemt_upstream_connect_attempt_total 564
telemt_upstream_connect_success_total 558
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 564
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 278
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_reconnect_attempts_total 362
telemt_me_reconnect_success_total 362
telemt_me_reader_eof_total 355
telemt_me_idle_close_by_peer_total 355
telemt_me_route_drop_no_conn_total 12628
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30788
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 21
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 8
telemt_desync_frames_bucket_total{bucket="gt_10"} 9
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 368
telemt_me_writer_restored_same_endpoint_total 352
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 30784
telemt_user_connections_current{user="hello"} 672
telemt_user_octets_from_client{user="hello"} 373394280 (356.10 MB)
telemt_user_octets_to_client{user="hello"} 17562659852 (16.36 GB)
telemt_user_unique_ips_current{user="hello"} 215
telemt_user_unique_ips_recent_window{user="hello"} 80
```