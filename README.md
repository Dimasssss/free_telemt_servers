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

# Server Metrics 2026-03-13 00:33:49 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 61225.8 (17h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 257297
telemt_connections_bad_total 2754
telemt_handshake_timeouts_total 5287
telemt_upstream_connect_attempt_total 15378
telemt_upstream_connect_success_total 15311
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 15378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6766
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8499
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1496
telemt_me_reconnect_attempts_total 15707
telemt_me_reconnect_success_total 12234
telemt_me_reader_eof_total 13040
telemt_me_idle_close_by_peer_total 13039
telemt_me_route_drop_no_conn_total 80021
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213144
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 717
telemt_desync_full_logged_total 267
telemt_desync_suppressed_total 450
telemt_desync_frames_bucket_total{bucket="1_2"} 125
telemt_desync_frames_bucket_total{bucket="3_10"} 267
telemt_desync_frames_bucket_total{bucket="gt_10"} 325
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12479
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 12218
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 245
telemt_user_connections_total{user="hello"} 212912
telemt_user_connections_current{user="hello"} 207
telemt_user_octets_from_client{user="hello"} 3899021432 (3.63 GB)
telemt_user_octets_to_client{user="hello"} 108218227608 (100.79 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 61118.6 (16h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 119035
telemt_connections_bad_total 711
telemt_handshake_timeouts_total 965
telemt_upstream_connect_attempt_total 34679
telemt_upstream_connect_success_total 34276
telemt_upstream_connect_fail_total 403
telemt_upstream_connect_attempts_per_request{bucket="1"} 34679
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21905
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11870
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 403
telemt_me_keepalive_timeout_total 432
telemt_me_reconnect_attempts_total 56590
telemt_me_reconnect_success_total 14718
telemt_me_reader_eof_total 16409
telemt_me_idle_close_by_peer_total 16409
telemt_me_route_drop_no_conn_total 42690
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 96442
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 14
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
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 16134
telemt_me_refill_failed_total 1307
telemt_me_writer_restored_same_endpoint_total 14703
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1416
telemt_user_connections_total{user="hello"} 112942
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 1230606004 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 34623703583 (32.25 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 32
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 61082.2 (16h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 144412
telemt_connections_bad_total 1668
telemt_handshake_timeouts_total 2324
telemt_upstream_connect_attempt_total 16767
telemt_upstream_connect_success_total 16765
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 16767
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8909
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 358
telemt_me_reconnect_attempts_total 14818
telemt_me_reconnect_success_total 13666
telemt_me_reader_eof_total 14601
telemt_me_idle_close_by_peer_total 14601
telemt_me_route_drop_no_conn_total 54832
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 135019
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 52
telemt_desync_full_logged_total 26
telemt_desync_suppressed_total 26
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 13
telemt_desync_frames_bucket_total{bucket="gt_10"} 36
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 13835
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 13646
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 169
telemt_user_connections_total{user="hello"} 134983
telemt_user_connections_current{user="hello"} 86
telemt_user_octets_from_client{user="hello"} 2624785860 (2.44 GB)
telemt_user_octets_to_client{user="hello"} 62227982740 (57.95 GB)
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 61058.0 (16h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207477
telemt_connections_bad_total 13285
telemt_handshake_timeouts_total 1411
telemt_upstream_connect_attempt_total 28806
telemt_upstream_connect_success_total 19067
telemt_upstream_connect_fail_total 9739
telemt_upstream_connect_attempts_per_request{bucket="1"} 28806
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9881
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9033
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 145
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9739
telemt_me_keepalive_timeout_total 3197
telemt_me_reconnect_attempts_total 47446
telemt_me_reconnect_success_total 13143
telemt_me_reader_eof_total 14675
telemt_me_idle_close_by_peer_total 14668
telemt_me_route_drop_no_conn_total 74117
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 171320
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 499
telemt_desync_full_logged_total 143
telemt_desync_suppressed_total 356
telemt_desync_frames_bucket_total{bucket="1_2"} 124
telemt_desync_frames_bucket_total{bucket="3_10"} 186
telemt_desync_frames_bucket_total{bucket="gt_10"} 189
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 14414
telemt_me_refill_failed_total 1068
telemt_me_writer_restored_same_endpoint_total 13133
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1271
telemt_user_connections_total{user="hello"} 174074
telemt_user_connections_current{user="hello"} 112
telemt_user_octets_from_client{user="hello"} 3008287778 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 71729284121 (66.80 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 34
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 11229.7 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10096
telemt_connections_bad_total 2071
telemt_handshake_timeouts_total 22
telemt_upstream_connect_attempt_total 3538
telemt_upstream_connect_success_total 3503
telemt_upstream_connect_fail_total 35
telemt_upstream_connect_attempts_per_request{bucket="1"} 3538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1554
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1934
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 35
telemt_me_keepalive_timeout_total 63
telemt_me_reconnect_attempts_total 2919
telemt_me_reconnect_success_total 2913
telemt_me_reader_eof_total 3101
telemt_me_idle_close_by_peer_total 3101
telemt_me_route_drop_no_conn_total 3117
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7663
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 11
telemt_me_writer_removed_unexpected_total 2927
telemt_me_writer_restored_same_endpoint_total 2897
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 7663
telemt_user_connections_current{user="hello"} 33
telemt_user_octets_from_client{user="hello"} 29246488 (27.89 MB)
telemt_user_octets_to_client{user="hello"} 2746224220 (2.56 GB)
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 61014.5 (16h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 345947
telemt_connections_bad_total 6491
telemt_handshake_timeouts_total 2562
telemt_upstream_connect_attempt_total 12866
telemt_upstream_connect_success_total 12796
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 12866
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5994
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6782
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_timeout_total 1330
telemt_me_reconnect_attempts_total 13372
telemt_me_reconnect_success_total 9755
telemt_me_reader_eof_total 10465
telemt_me_idle_close_by_peer_total 10463
telemt_me_route_drop_no_conn_total 154672
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 338624
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 299
telemt_desync_full_logged_total 116
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 113
telemt_pool_swap_total 53
telemt_me_writer_removed_unexpected_total 9987
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 9748
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 232
telemt_user_connections_total{user="hello"} 326925
telemt_user_connections_current{user="hello"} 255
telemt_user_octets_from_client{user="hello"} 5583299088 (5.20 GB)
telemt_user_octets_to_client{user="hello"} 175812131188 (163.74 GB)
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 34
```