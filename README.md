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

# Server Metrics 2026-03-13 09:21:02 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 92858.6 (25h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 363499
telemt_connections_bad_total 3187
telemt_handshake_timeouts_total 7821
telemt_upstream_connect_attempt_total 23471
telemt_upstream_connect_success_total 23362
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 23471
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10543
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1714
telemt_me_reconnect_attempts_total 22196
telemt_me_reconnect_success_total 18684
telemt_me_reader_eof_total 19968
telemt_me_idle_close_by_peer_total 19967
telemt_me_route_drop_no_conn_total 114306
telemt_me_route_drop_channel_closed_total 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 311332
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 991
telemt_desync_full_logged_total 369
telemt_desync_suppressed_total 622
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 361
telemt_desync_frames_bucket_total{bucket="gt_10"} 423
telemt_pool_swap_total 84
telemt_me_writer_removed_unexpected_total 18989
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 18668
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 305
telemt_user_connections_total{user="hello"} 311024
telemt_user_connections_current{user="hello"} 354
telemt_user_octets_from_client{user="hello"} 5069320528 (4.72 GB)
telemt_user_octets_to_client{user="hello"} 139453693288 (129.88 GB)
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 45
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 92751.4 (25h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 166072
telemt_connections_bad_total 1541
telemt_handshake_timeouts_total 1280
telemt_upstream_connect_attempt_total 46236
telemt_upstream_connect_success_total 45607
telemt_upstream_connect_fail_total 629
telemt_upstream_connect_attempts_per_request{bucket="1"} 46236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 26399
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18693
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 515
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 629
telemt_me_keepalive_timeout_total 705
telemt_me_reconnect_attempts_total 79870
telemt_me_reconnect_success_total 24495
telemt_me_reader_eof_total 26962
telemt_me_idle_close_by_peer_total 26962
telemt_me_route_drop_no_conn_total 63565
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 139779
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 32
telemt_desync_full_logged_total 10
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 18
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 26428
telemt_me_refill_failed_total 1728
telemt_me_writer_restored_same_endpoint_total 24480
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1933
telemt_user_connections_total{user="hello"} 156268
telemt_user_connections_current{user="hello"} 156
telemt_user_octets_from_client{user="hello"} 1628193100 (1.52 GB)
telemt_user_octets_to_client{user="hello"} 50298753735 (46.84 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 92715.1 (25h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 202855
telemt_connections_bad_total 2006
telemt_handshake_timeouts_total 4139
telemt_upstream_connect_attempt_total 25039
telemt_upstream_connect_success_total 25036
telemt_upstream_connect_fail_total 3
telemt_upstream_connect_attempts_per_request{bucket="1"} 25039
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13513
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 3
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 638
telemt_me_reconnect_attempts_total 21570
telemt_me_reconnect_success_total 20383
telemt_me_reader_eof_total 21859
telemt_me_idle_close_by_peer_total 21859
telemt_me_route_drop_no_conn_total 76649
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 189251
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 63
telemt_desync_full_logged_total 31
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 21
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 85
telemt_me_writer_removed_unexpected_total 20606
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 20363
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 223
telemt_user_connections_total{user="hello"} 189176
telemt_user_connections_current{user="hello"} 197
telemt_user_octets_from_client{user="hello"} 7339901952 (6.84 GB)
telemt_user_octets_to_client{user="hello"} 78700376180 (73.30 GB)
telemt_user_unique_ips_current{user="hello"} 67
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 92690.6 (25h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 288789
telemt_connections_bad_total 13663
telemt_handshake_timeouts_total 2139
telemt_upstream_connect_attempt_total 38141
telemt_upstream_connect_success_total 28147
telemt_upstream_connect_fail_total 9994
telemt_upstream_connect_attempts_per_request{bucket="1"} 38141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14058
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13894
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 186
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9994
telemt_me_keepalive_timeout_total 3423
telemt_me_reconnect_attempts_total 75966
telemt_me_reconnect_success_total 20675
telemt_me_reader_eof_total 23042
telemt_me_idle_close_by_peer_total 23035
telemt_me_route_drop_no_conn_total 104197
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 246569
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 910
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 643
telemt_desync_frames_bucket_total{bucket="1_2"} 230
telemt_desync_frames_bucket_total{bucket="3_10"} 340
telemt_desync_frames_bucket_total{bucket="gt_10"} 340
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 22664
telemt_me_refill_failed_total 1723
telemt_me_writer_restored_same_endpoint_total 20665
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1989
telemt_user_connections_total{user="hello"} 249293
telemt_user_connections_current{user="hello"} 199
telemt_user_octets_from_client{user="hello"} 5508505870 (5.13 GB)
telemt_user_octets_to_client{user="hello"} 94332053641 (87.85 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 64
telemt_user_unique_ips_recent_window{user="hello"} 31
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 42862.2 (11h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55617
telemt_connections_bad_total 8644
telemt_handshake_timeouts_total 470
telemt_upstream_connect_attempt_total 14881
telemt_upstream_connect_success_total 14735
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 14881
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6473
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8211
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 51
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 357
telemt_me_reconnect_attempts_total 14810
telemt_me_reconnect_success_total 12585
telemt_me_reader_eof_total 13409
telemt_me_idle_close_by_peer_total 13409
telemt_me_route_drop_no_conn_total 16851
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 44979
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 76
telemt_desync_full_logged_total 13
telemt_desync_suppressed_total 63
telemt_desync_frames_bucket_total{bucket="1_2"} 7
telemt_desync_frames_bucket_total{bucket="3_10"} 32
telemt_desync_frames_bucket_total{bucket="gt_10"} 37
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 12766
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 12567
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 181
telemt_user_connections_total{user="hello"} 44974
telemt_user_connections_current{user="hello"} 90
telemt_user_octets_from_client{user="hello"} 331648928 (316.29 MB)
telemt_user_octets_to_client{user="hello"} 12268402864 (11.43 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 92647.2 (25h 44m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 498231
telemt_connections_bad_total 13770
telemt_handshake_timeouts_total 5200
telemt_upstream_connect_attempt_total 19594
telemt_upstream_connect_success_total 19490
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 19594
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9123
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10342
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_timeout_total 1541
telemt_me_reconnect_attempts_total 18547
telemt_me_reconnect_success_total 14902
telemt_me_reader_eof_total 15996
telemt_me_idle_close_by_peer_total 15993
telemt_me_route_drop_no_conn_total 260368
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 488612
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 398
telemt_desync_full_logged_total 152
telemt_desync_suppressed_total 246
telemt_desync_frames_bucket_total{bucket="1_2"} 94
telemt_desync_frames_bucket_total{bucket="3_10"} 143
telemt_desync_frames_bucket_total{bucket="gt_10"} 161
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 15209
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 14895
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 307
telemt_user_connections_total{user="hello"} 461703
telemt_user_connections_current{user="hello"} 394
telemt_user_octets_from_client{user="hello"} 8409924432 (7.83 GB)
telemt_user_octets_to_client{user="hello"} 260339612704 (242.46 GB)
telemt_user_unique_ips_current{user="hello"} 155
telemt_user_unique_ips_recent_window{user="hello"} 65
```