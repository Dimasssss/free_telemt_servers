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

# Server Metrics 2026-03-12 14:30:30 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 25027.0 (6h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 132316
telemt_connections_bad_total 1373
telemt_handshake_timeouts_total 4515
telemt_upstream_connect_attempt_total 6106
telemt_upstream_connect_success_total 6082
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 6106
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2683
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3393
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 267
telemt_me_reconnect_attempts_total 4828
telemt_me_reconnect_success_total 4796
telemt_me_reader_eof_total 5041
telemt_me_idle_close_by_peer_total 5040
telemt_me_route_drop_no_conn_total 37566
telemt_me_route_drop_channel_closed_total 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 115699
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 553
telemt_desync_full_logged_total 206
telemt_desync_suppressed_total 347
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 218
telemt_desync_frames_bucket_total{bucket="gt_10"} 232
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 4838
telemt_me_writer_restored_same_endpoint_total 4780
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 42
telemt_user_connections_total{user="hello"} 115661
telemt_user_connections_current{user="hello"} 361
telemt_user_octets_from_client{user="hello"} 1942498768 (1.81 GB)
telemt_user_octets_to_client{user="hello"} 43387293084 (40.41 GB)
telemt_user_unique_ips_current{user="hello"} 106
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 24920.0 (6h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 54701
telemt_connections_bad_total 445
telemt_handshake_timeouts_total 362
telemt_upstream_connect_attempt_total 7497
telemt_upstream_connect_success_total 7326
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 7497
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3037
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4261
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_timeout_total 164
telemt_me_reconnect_attempts_total 21896
telemt_me_reconnect_success_total 6062
telemt_me_reader_eof_total 6675
telemt_me_idle_close_by_peer_total 6675
telemt_me_route_drop_no_conn_total 24471
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 52235
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 31
telemt_desync_full_logged_total 9
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 17
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 6596
telemt_me_refill_failed_total 494
telemt_me_writer_restored_same_endpoint_total 6047
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 534
telemt_user_connections_total{user="hello"} 52229
telemt_user_connections_current{user="hello"} 174
telemt_user_octets_from_client{user="hello"} 606251104 (578.17 MB)
telemt_user_octets_to_client{user="hello"} 15456958064 (14.40 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 24883.5 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75503
telemt_connections_bad_total 1417
telemt_handshake_timeouts_total 1181
telemt_upstream_connect_attempt_total 6733
telemt_upstream_connect_success_total 6733
telemt_upstream_connect_attempts_per_request{bucket="1"} 6733
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3272
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3451
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 5475
telemt_me_reconnect_success_total 5432
telemt_me_reader_eof_total 5734
telemt_me_idle_close_by_peer_total 5734
telemt_me_route_drop_no_conn_total 26449
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 69685
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
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5470
telemt_me_writer_restored_same_endpoint_total 5412
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 38
telemt_user_connections_total{user="hello"} 69663
telemt_user_connections_current{user="hello"} 250
telemt_user_octets_from_client{user="hello"} 1915251216 (1.78 GB)
telemt_user_octets_to_client{user="hello"} 39791592780 (37.06 GB)
telemt_user_unique_ips_current{user="hello"} 84
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 24859.2 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 95912
telemt_connections_bad_total 2453
telemt_handshake_timeouts_total 718
telemt_upstream_connect_attempt_total 6462
telemt_upstream_connect_success_total 6293
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 6462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2811
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 22
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 252
telemt_me_reconnect_attempts_total 19464
telemt_me_reconnect_success_total 5012
telemt_me_reader_eof_total 5596
telemt_me_idle_close_by_peer_total 5596
telemt_me_route_drop_no_conn_total 35380
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 87263
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 278
telemt_desync_full_logged_total 93
telemt_desync_suppressed_total 185
telemt_desync_frames_bucket_total{bucket="1_2"} 100
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 84
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 5521
telemt_me_refill_failed_total 450
telemt_me_writer_restored_same_endpoint_total 5004
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 509
telemt_user_connections_total{user="hello"} 87146
telemt_user_connections_current{user="hello"} 230
telemt_user_octets_from_client{user="hello"} 1511257284 (1.41 GB)
telemt_user_octets_to_client{user="hello"} 36702478488 (34.18 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 41
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 24828.7 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 56077
telemt_connections_bad_total 4770
telemt_handshake_timeouts_total 709
telemt_upstream_connect_attempt_total 21600
telemt_upstream_connect_success_total 21291
telemt_upstream_connect_fail_total 309
telemt_upstream_connect_attempts_per_request{bucket="1"} 21600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17060
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 309
telemt_me_keepalive_timeout_total 105
telemt_me_reconnect_attempts_total 32831
telemt_me_reconnect_success_total 3684
telemt_me_reader_eof_total 4591
telemt_me_idle_close_by_peer_total 4591
telemt_me_seq_mismatch_total 8
telemt_me_route_drop_no_conn_total 12308
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 32951
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 443
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 16
telemt_desync_frames_bucket_total{bucket="3_10"} 369
telemt_desync_frames_bucket_total{bucket="gt_10"} 58
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 4616
telemt_me_refill_failed_total 912
telemt_me_writer_restored_same_endpoint_total 3667
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 932
telemt_user_connections_total{user="hello"} 49279
telemt_user_connections_current{user="hello"} 143
telemt_user_octets_from_client{user="hello"} 410137735 (391.14 MB)
telemt_user_octets_to_client{user="hello"} 12304381507 (11.46 GB)
telemt_user_msgs_from_client{user="hello"} 235515
telemt_user_msgs_to_client{user="hello"} 672828
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 24815.9 (6h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 151059
telemt_connections_bad_total 782
telemt_handshake_timeouts_total 1173
telemt_upstream_connect_attempt_total 5107
telemt_upstream_connect_success_total 5080
telemt_upstream_connect_fail_total 27
telemt_upstream_connect_attempts_per_request{bucket="1"} 5107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2412
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 27
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 3842
telemt_me_reconnect_success_total 3812
telemt_me_reader_eof_total 4017
telemt_me_idle_close_by_peer_total 4017
telemt_me_route_drop_no_conn_total 59276
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144440
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 230
telemt_desync_full_logged_total 84
telemt_desync_suppressed_total 146
telemt_desync_frames_bucket_total{bucket="1_2"} 56
telemt_desync_frames_bucket_total{bucket="3_10"} 88
telemt_desync_frames_bucket_total{bucket="gt_10"} 86
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 3856
telemt_me_writer_restored_same_endpoint_total 3805
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 144406
telemt_user_connections_current{user="hello"} 511
telemt_user_octets_from_client{user="hello"} 2907843356 (2.71 GB)
telemt_user_octets_to_client{user="hello"} 60575485864 (56.42 GB)
telemt_user_unique_ips_current{user="hello"} 166
telemt_user_unique_ips_recent_window{user="hello"} 106
```