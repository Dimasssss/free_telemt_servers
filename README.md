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

# Server Metrics 2026-03-12 17:14:24 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 34861.2 (9h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 182457
telemt_connections_bad_total 2388
telemt_handshake_timeouts_total 4913
telemt_upstream_connect_attempt_total 8799
telemt_upstream_connect_success_total 8767
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 8799
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3889
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 365
telemt_me_reconnect_attempts_total 8115
telemt_me_reconnect_success_total 6975
telemt_me_reader_eof_total 7343
telemt_me_idle_close_by_peer_total 7342
telemt_me_route_drop_no_conn_total 53114
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155071
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 624
telemt_desync_full_logged_total 233
telemt_desync_suppressed_total 391
telemt_desync_frames_bucket_total{bucket="1_2"} 120
telemt_desync_frames_bucket_total{bucket="3_10"} 237
telemt_desync_frames_bucket_total{bucket="gt_10"} 267
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7083
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 6959
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 155032
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 2671125092 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 63684431520 (59.31 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 34754.2 (9h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 76720
telemt_connections_bad_total 467
telemt_handshake_timeouts_total 643
telemt_upstream_connect_attempt_total 10848
telemt_upstream_connect_success_total 10619
telemt_upstream_connect_fail_total 229
telemt_upstream_connect_attempts_per_request{bucket="1"} 10848
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6285
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 85
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 229
telemt_me_keepalive_timeout_total 301
telemt_me_reconnect_attempts_total 34684
telemt_me_reconnect_success_total 8860
telemt_me_reader_eof_total 9836
telemt_me_idle_close_by_peer_total 9836
telemt_me_route_drop_no_conn_total 33850
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 72858
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 8
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 9735
telemt_me_refill_failed_total 806
telemt_me_writer_restored_same_endpoint_total 8845
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 875
telemt_user_connections_total{user="hello"} 72843
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 814962064 (777.21 MB)
telemt_user_octets_to_client{user="hello"} 20218036924 (18.83 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 34717.4 (9h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 103325
telemt_connections_bad_total 1496
telemt_handshake_timeouts_total 2061
telemt_upstream_connect_attempt_total 9603
telemt_upstream_connect_success_total 9603
telemt_upstream_connect_attempts_per_request{bucket="1"} 9603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4656
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4937
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 7857
telemt_me_reconnect_success_total 7787
telemt_me_reader_eof_total 8247
telemt_me_idle_close_by_peer_total 8247
telemt_me_route_drop_no_conn_total 38556
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 95550
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 38
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 20
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 11
telemt_desync_frames_bucket_total{bucket="gt_10"} 25
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 7858
telemt_me_writer_restored_same_endpoint_total 7767
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 95522
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 2294729172 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 50171684628 (46.73 GB)
telemt_user_unique_ips_current{user="hello"} 63
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 34693.2 (9h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 141987
telemt_connections_bad_total 13067
telemt_handshake_timeouts_total 1076
telemt_upstream_connect_attempt_total 7509
telemt_upstream_connect_success_total 7272
telemt_upstream_connect_fail_total 237
telemt_upstream_connect_attempts_per_request{bucket="1"} 7509
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3387
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3857
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 237
telemt_me_keepalive_timeout_total 357
telemt_me_reconnect_attempts_total 33587
telemt_me_reconnect_success_total 5498
telemt_me_reader_eof_total 6509
telemt_me_idle_close_by_peer_total 6509
telemt_me_route_drop_no_conn_total 50983
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 120679
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 407
telemt_desync_full_logged_total 120
telemt_desync_suppressed_total 287
telemt_desync_frames_bucket_total{bucket="1_2"} 117
telemt_desync_frames_bucket_total{bucket="3_10"} 152
telemt_desync_frames_bucket_total{bucket="gt_10"} 138
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 6437
telemt_me_refill_failed_total 876
telemt_me_writer_restored_same_endpoint_total 5490
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 939
telemt_user_connections_total{user="hello"} 120561
telemt_user_connections_current{user="hello"} 180
telemt_user_octets_from_client{user="hello"} 2185573048 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 51359089964 (47.83 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 34662.6 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 85561
telemt_connections_bad_total 9156
telemt_handshake_timeouts_total 1137
telemt_upstream_connect_attempt_total 44380
telemt_upstream_connect_success_total 43953
telemt_upstream_connect_fail_total 427
telemt_upstream_connect_attempts_per_request{bucket="1"} 44380
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37539
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6374
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 427
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 47853
telemt_me_reconnect_success_total 3707
telemt_me_reader_eof_total 5084
telemt_me_idle_close_by_peer_total 5084
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 13103
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34685
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 25
telemt_me_hardswap_pending_ttl_expired_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 448
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 323
telemt_desync_frames_bucket_total{bucket="1_2"} 17
telemt_desync_frames_bucket_total{bucket="3_10"} 372
telemt_desync_frames_bucket_total{bucket="gt_10"} 59
telemt_pool_swap_total 1
telemt_me_writer_removed_unexpected_total 5112
telemt_me_refill_failed_total 1382
telemt_me_writer_restored_same_endpoint_total 3690
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1405
telemt_user_connections_total{user="hello"} 73158
telemt_user_connections_current{user="hello"} 147
telemt_user_octets_from_client{user="hello"} 681632039 (650.05 MB)
telemt_user_octets_to_client{user="hello"} 22232710255 (20.71 GB)
telemt_user_msgs_from_client{user="hello"} 619477
telemt_user_msgs_to_client{user="hello"} 2331204
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 26
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 34649.9 (9h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 220339
telemt_connections_bad_total 974
telemt_handshake_timeouts_total 1762
telemt_upstream_connect_attempt_total 7466
telemt_upstream_connect_success_total 7429
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 7466
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3944
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 421
telemt_me_reconnect_attempts_total 7879
telemt_me_reconnect_success_total 5657
telemt_me_reader_eof_total 5992
telemt_me_idle_close_by_peer_total 5991
telemt_me_route_drop_no_conn_total 100502
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 220507
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 255
telemt_desync_full_logged_total 101
telemt_desync_suppressed_total 154
telemt_desync_frames_bucket_total{bucket="1_2"} 68
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5801
telemt_me_refill_failed_total 68
telemt_me_writer_restored_same_endpoint_total 5650
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 144
telemt_user_connections_total{user="hello"} 210442
telemt_user_connections_current{user="hello"} 489
telemt_user_octets_from_client{user="hello"} 3833930532 (3.57 GB)
telemt_user_octets_to_client{user="hello"} 96997653728 (90.34 GB)
telemt_user_unique_ips_current{user="hello"} 158
telemt_user_unique_ips_recent_window{user="hello"} 53
```