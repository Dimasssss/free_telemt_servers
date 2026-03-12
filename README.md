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

# Server Metrics 2026-03-12 10:50:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 11840.0 (3h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 61665
telemt_connections_bad_total 493
telemt_handshake_timeouts_total 2501
telemt_upstream_connect_attempt_total 2940
telemt_upstream_connect_success_total 2928
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2940
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1329
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1597
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 2296
telemt_me_reconnect_success_total 2283
telemt_me_reader_eof_total 2365
telemt_me_idle_close_by_peer_total 2364
telemt_me_route_drop_no_conn_total 16779
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55569
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 207
telemt_desync_full_logged_total 82
telemt_desync_suppressed_total 125
telemt_desync_frames_bucket_total{bucket="1_2"} 42
telemt_desync_frames_bucket_total{bucket="3_10"} 75
telemt_desync_frames_bucket_total{bucket="gt_10"} 90
telemt_pool_swap_total 10
telemt_me_writer_removed_unexpected_total 2295
telemt_me_writer_restored_same_endpoint_total 2267
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 12
telemt_user_connections_total{user="hello"} 55542
telemt_user_connections_current{user="hello"} 303
telemt_user_octets_from_client{user="hello"} 774362624 (738.49 MB)
telemt_user_octets_to_client{user="hello"} 16645995340 (15.50 GB)
telemt_user_unique_ips_current{user="hello"} 90
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 11733.1 (3h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 25155
telemt_connections_bad_total 187
telemt_handshake_timeouts_total 187
telemt_upstream_connect_attempt_total 4256
telemt_upstream_connect_success_total 4176
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 4255
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1569
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2605
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 8487
telemt_me_reconnect_success_total 3578
telemt_me_reader_eof_total 3774
telemt_me_idle_close_by_peer_total 3774
telemt_me_route_drop_no_conn_total 9507
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 23947
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 30
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 2
telemt_me_writer_removed_unexpected_total 3744
telemt_me_refill_failed_total 153
telemt_me_writer_restored_same_endpoint_total 3563
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 166
telemt_user_connections_total{user="hello"} 23945
telemt_user_connections_current{user="hello"} 130
telemt_user_octets_from_client{user="hello"} 251038924 (239.41 MB)
telemt_user_octets_to_client{user="hello"} 5218260200 (4.86 GB)
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 11698.2 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 35511
telemt_connections_bad_total 102
telemt_handshake_timeouts_total 260
telemt_upstream_connect_attempt_total 3243
telemt_upstream_connect_success_total 3243
telemt_upstream_connect_attempts_per_request{bucket="1"} 3243
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1611
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1628
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 53
telemt_me_reconnect_attempts_total 2651
telemt_me_reconnect_success_total 2634
telemt_me_reader_eof_total 2736
telemt_me_idle_close_by_peer_total 2736
telemt_me_route_drop_no_conn_total 11459
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 33194
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10
telemt_desync_full_logged_total 6
telemt_desync_suppressed_total 4
telemt_desync_frames_bucket_total{bucket="3_10"} 6
telemt_desync_frames_bucket_total{bucket="gt_10"} 4
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 2636
telemt_me_writer_restored_same_endpoint_total 2614
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 2
telemt_user_connections_total{user="hello"} 33184
telemt_user_connections_current{user="hello"} 214
telemt_user_octets_from_client{user="hello"} 434993380 (414.84 MB)
telemt_user_octets_to_client{user="hello"} 28723248884 (26.75 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 11672.6 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 42659
telemt_connections_bad_total 1031
telemt_handshake_timeouts_total 224
telemt_upstream_connect_attempt_total 3323
telemt_upstream_connect_success_total 3247
telemt_upstream_connect_fail_total 76
telemt_upstream_connect_attempts_per_request{bucket="1"} 3323
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1366
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1872
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 76
telemt_me_keepalive_timeout_total 156
telemt_me_reconnect_attempts_total 2678
telemt_me_reconnect_success_total 2641
telemt_me_reader_eof_total 2749
telemt_me_idle_close_by_peer_total 2749
telemt_me_route_drop_no_conn_total 12877
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 38612
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 160
telemt_desync_full_logged_total 56
telemt_desync_suppressed_total 104
telemt_desync_frames_bucket_total{bucket="1_2"} 64
telemt_desync_frames_bucket_total{bucket="3_10"} 54
telemt_desync_frames_bucket_total{bucket="gt_10"} 42
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 2680
telemt_me_writer_restored_same_endpoint_total 2633
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 38611
telemt_user_connections_current{user="hello"} 177
telemt_user_octets_from_client{user="hello"} 903459480 (861.61 MB)
telemt_user_octets_to_client{user="hello"} 25093093708 (23.37 GB)
telemt_user_unique_ips_current{user="hello"} 56
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 11641.8 (3h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22365
telemt_connections_bad_total 2240
telemt_handshake_timeouts_total 343
telemt_upstream_connect_attempt_total 3726
telemt_upstream_connect_success_total 3599
telemt_upstream_connect_fail_total 127
telemt_upstream_connect_attempts_per_request{bucket="1"} 3726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1284
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2306
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 127
telemt_me_keepalive_timeout_total 78
telemt_me_reconnect_attempts_total 11813
telemt_me_reconnect_success_total 2996
telemt_me_reader_eof_total 3263
telemt_me_idle_close_by_peer_total 3263
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 6704
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19132
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 310
telemt_desync_full_logged_total 89
telemt_desync_suppressed_total 221
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 262
telemt_desync_frames_bucket_total{bucket="gt_10"} 41
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 3285
telemt_me_refill_failed_total 275
telemt_me_writer_restored_same_endpoint_total 2980
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 289
telemt_user_connections_total{user="hello"} 19129
telemt_user_connections_current{user="hello"} 85
telemt_user_octets_from_client{user="hello"} 91435124 (87.20 MB)
telemt_user_octets_to_client{user="hello"} 5293873376 (4.93 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 11628.8 (3h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58817
telemt_connections_bad_total 575
telemt_handshake_timeouts_total 688
telemt_upstream_connect_attempt_total 2267
telemt_upstream_connect_success_total 2255
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 2267
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1091
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1162
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 1674
telemt_me_reconnect_success_total 1660
telemt_me_reader_eof_total 1734
telemt_me_idle_close_by_peer_total 1734
telemt_me_route_drop_no_conn_total 25845
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 55430
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 138
telemt_desync_full_logged_total 47
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 39
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 52
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 1681
telemt_me_writer_restored_same_endpoint_total 1653
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 55394
telemt_user_connections_current{user="hello"} 387
telemt_user_octets_from_client{user="hello"} 1900159204 (1.77 GB)
telemt_user_octets_to_client{user="hello"} 32032374484 (29.83 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 50
```