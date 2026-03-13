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

# Server Metrics 2026-03-13 06:37:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 83025.5 (23h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 314304
telemt_connections_bad_total 3129
telemt_handshake_timeouts_total 6713
telemt_upstream_connect_attempt_total 20935
telemt_upstream_connect_success_total 20837
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 20935
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9398
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11391
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1621
telemt_me_reconnect_attempts_total 20156
telemt_me_reconnect_success_total 16653
telemt_me_reader_eof_total 17809
telemt_me_idle_close_by_peer_total 17808
telemt_me_route_drop_no_conn_total 97841
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 265718
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 926
telemt_desync_full_logged_total 343
telemt_desync_suppressed_total 583
telemt_desync_frames_bucket_total{bucket="1_2"} 184
telemt_desync_frames_bucket_total{bucket="3_10"} 336
telemt_desync_frames_bucket_total{bucket="gt_10"} 406
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 16941
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 16637
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 288
telemt_user_connections_total{user="hello"} 265649
telemt_user_connections_current{user="hello"} 276
telemt_user_octets_from_client{user="hello"} 4506675968 (4.20 GB)
telemt_user_octets_to_client{user="hello"} 126475390844 (117.79 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 82918.3 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144109
telemt_connections_bad_total 1422
telemt_handshake_timeouts_total 1063
telemt_upstream_connect_attempt_total 43221
telemt_upstream_connect_success_total 42657
telemt_upstream_connect_fail_total 564
telemt_upstream_connect_attempts_per_request{bucket="1"} 43221
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25223
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 509
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 564
telemt_me_keepalive_timeout_total 626
telemt_me_reconnect_attempts_total 71189
telemt_me_reconnect_success_total 21997
telemt_me_reader_eof_total 24206
telemt_me_idle_close_by_peer_total 24206
telemt_me_route_drop_no_conn_total 54261
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 119917
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 17
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
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 23705
telemt_me_refill_failed_total 1535
telemt_me_writer_restored_same_endpoint_total 21982
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1708
telemt_user_connections_total{user="hello"} 136412
telemt_user_connections_current{user="hello"} 148
telemt_user_octets_from_client{user="hello"} 1412180332 (1.32 GB)
telemt_user_octets_to_client{user="hello"} 43488642407 (40.50 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 82882.1 (23h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 174549
telemt_connections_bad_total 1912
telemt_handshake_timeouts_total 2856
telemt_upstream_connect_attempt_total 22706
telemt_upstream_connect_success_total 22704
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 22706
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10470
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12211
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 502
telemt_me_reconnect_attempts_total 19679
telemt_me_reconnect_success_total 18507
telemt_me_reader_eof_total 19835
telemt_me_idle_close_by_peer_total 19835
telemt_me_route_drop_no_conn_total 67363
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163289
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 62
telemt_desync_full_logged_total 30
telemt_desync_suppressed_total 32
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 20
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 75
telemt_me_writer_removed_unexpected_total 18707
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 18487
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 200
telemt_user_connections_total{user="hello"} 163216
telemt_user_connections_current{user="hello"} 108
telemt_user_octets_from_client{user="hello"} 2962763340 (2.76 GB)
telemt_user_octets_to_client{user="hello"} 73064078616 (68.05 GB)
telemt_user_unique_ips_current{user="hello"} 48
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 82857.5 (23h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 251762
telemt_connections_bad_total 13611
telemt_handshake_timeouts_total 1921
telemt_upstream_connect_attempt_total 35121
telemt_upstream_connect_success_total 25194
telemt_upstream_connect_fail_total 9927
telemt_upstream_connect_attempts_per_request{bucket="1"} 35121
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12356
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9927
telemt_me_keepalive_timeout_total 3349
telemt_me_reconnect_attempts_total 69741
telemt_me_reconnect_success_total 18204
telemt_me_reader_eof_total 20380
telemt_me_idle_close_by_peer_total 20373
telemt_me_route_drop_no_conn_total 91330
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 212120
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 643
telemt_desync_full_logged_total 187
telemt_desync_suppressed_total 456
telemt_desync_frames_bucket_total{bucket="1_2"} 161
telemt_desync_frames_bucket_total{bucket="3_10"} 243
telemt_desync_frames_bucket_total{bucket="gt_10"} 239
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 20046
telemt_me_refill_failed_total 1606
telemt_me_writer_restored_same_endpoint_total 18194
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1842
telemt_user_connections_total{user="hello"} 214854
telemt_user_connections_current{user="hello"} 159
telemt_user_octets_from_client{user="hello"} 4307592994 (4.01 GB)
telemt_user_octets_to_client{user="hello"} 82934480329 (77.24 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 23
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 33029.0 (9h 10m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 38038
telemt_connections_bad_total 6846
telemt_handshake_timeouts_total 160
telemt_upstream_connect_attempt_total 11394
telemt_upstream_connect_success_total 11284
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 11394
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6344
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_keepalive_timeout_total 273
telemt_me_reconnect_attempts_total 10592
telemt_me_reconnect_success_total 9627
telemt_me_reader_eof_total 10266
telemt_me_idle_close_by_peer_total 10266
telemt_me_route_drop_no_conn_total 10529
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 30048
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 9743
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 9609
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 116
telemt_user_connections_total{user="hello"} 30048
telemt_user_connections_current{user="hello"} 62
telemt_user_octets_from_client{user="hello"} 228193748 (217.62 MB)
telemt_user_octets_to_client{user="hello"} 10110942488 (9.42 GB)
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 82813.9 (23h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 425031
telemt_connections_bad_total 8064
telemt_handshake_timeouts_total 3234
telemt_upstream_connect_attempt_total 17614
telemt_upstream_connect_success_total 17518
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 17614
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8158
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9335
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 1456
telemt_me_reconnect_attempts_total 17055
telemt_me_reconnect_success_total 13421
telemt_me_reader_eof_total 14412
telemt_me_idle_close_by_peer_total 14409
telemt_me_route_drop_no_conn_total 188517
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 411917
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 361
telemt_desync_full_logged_total 138
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 87
telemt_desync_frames_bucket_total{bucket="3_10"} 128
telemt_desync_frames_bucket_total{bucket="gt_10"} 146
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 13703
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 13414
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 282
telemt_user_connections_total{user="hello"} 400152
telemt_user_connections_current{user="hello"} 362
telemt_user_octets_from_client{user="hello"} 6512715696 (6.07 GB)
telemt_user_octets_to_client{user="hello"} 233534321988 (217.50 GB)
telemt_user_unique_ips_current{user="hello"} 137
telemt_user_unique_ips_recent_window{user="hello"} 50
```