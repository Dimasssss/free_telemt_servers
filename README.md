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

# Server Metrics 2026-03-13 03:02:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 70127.7 (19h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 275352
telemt_connections_bad_total 2912
telemt_handshake_timeouts_total 5664
telemt_upstream_connect_attempt_total 17742
telemt_upstream_connect_success_total 17663
telemt_upstream_connect_fail_total 79
telemt_upstream_connect_attempts_per_request{bucket="1"} 17742
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7822
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9795
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 79
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1524
telemt_me_reconnect_attempts_total 17630
telemt_me_reconnect_success_total 14146
telemt_me_reader_eof_total 15112
telemt_me_idle_close_by_peer_total 15111
telemt_me_route_drop_no_conn_total 85691
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 229606
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 768
telemt_desync_full_logged_total 284
telemt_desync_suppressed_total 484
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 279
telemt_desync_frames_bucket_total{bucket="gt_10"} 349
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 14409
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 14130
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 263
telemt_user_connections_total{user="hello"} 229408
telemt_user_connections_current{user="hello"} 258
telemt_user_octets_from_client{user="hello"} 4061320692 (3.78 GB)
telemt_user_octets_to_client{user="hello"} 112637184280 (104.90 GB)
telemt_user_unique_ips_current{user="hello"} 70
telemt_user_unique_ips_recent_window{user="hello"} 28
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 70020.5 (19h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 127134
telemt_connections_bad_total 742
telemt_handshake_timeouts_total 982
telemt_upstream_connect_attempt_total 38619
telemt_upstream_connect_success_total 38152
telemt_upstream_connect_fail_total 467
telemt_upstream_connect_attempts_per_request{bucket="1"} 38619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23331
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14318
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 503
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 467
telemt_me_keepalive_timeout_total 502
telemt_me_reconnect_attempts_total 63395
telemt_me_reconnect_success_total 18152
telemt_me_reader_eof_total 20057
telemt_me_idle_close_by_peer_total 20057
telemt_me_route_drop_no_conn_total 45719
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 104223
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 15
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
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 19702
telemt_me_refill_failed_total 1412
telemt_me_writer_restored_same_endpoint_total 18137
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1550
telemt_user_connections_total{user="hello"} 120723
telemt_user_connections_current{user="hello"} 84
telemt_user_octets_from_client{user="hello"} 1268223992 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 35721926671 (33.27 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 69984.1 (19h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 153114
telemt_connections_bad_total 1824
telemt_handshake_timeouts_total 2429
telemt_upstream_connect_attempt_total 19414
telemt_upstream_connect_success_total 19412
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 19414
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8969
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 387
telemt_me_reconnect_attempts_total 17031
telemt_me_reconnect_success_total 15870
telemt_me_reader_eof_total 16972
telemt_me_idle_close_by_peer_total 16972
telemt_me_route_drop_no_conn_total 58732
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 143198
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 56
telemt_desync_full_logged_total 27
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 3
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 38
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 16045
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 15850
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 175
telemt_user_connections_total{user="hello"} 143124
telemt_user_connections_current{user="hello"} 60
telemt_user_octets_from_client{user="hello"} 2730514156 (2.54 GB)
telemt_user_octets_to_client{user="hello"} 68630846348 (63.92 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 69959.7 (19h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219493
telemt_connections_bad_total 13457
telemt_handshake_timeouts_total 1439
telemt_upstream_connect_attempt_total 31748
telemt_upstream_connect_success_total 21925
telemt_upstream_connect_fail_total 9823
telemt_upstream_connect_attempts_per_request{bucket="1"} 31748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11045
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10712
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9823
telemt_me_keepalive_timeout_total 3281
telemt_me_reconnect_attempts_total 57743
telemt_me_reconnect_success_total 15562
telemt_me_reader_eof_total 17382
telemt_me_idle_close_by_peer_total 17375
telemt_me_route_drop_no_conn_total 79909
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182644
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 14
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
telemt_pool_swap_total 20
telemt_me_writer_removed_unexpected_total 17094
telemt_me_refill_failed_total 1314
telemt_me_writer_restored_same_endpoint_total 15552
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1532
telemt_user_connections_total{user="hello"} 185395
telemt_user_connections_current{user="hello"} 97
telemt_user_octets_from_client{user="hello"} 3118582786 (2.90 GB)
telemt_user_octets_to_client{user="hello"} 76008156193 (70.79 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 31
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 20131.4 (5h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 19050
telemt_connections_bad_total 3778
telemt_handshake_timeouts_total 35
telemt_upstream_connect_attempt_total 6178
telemt_upstream_connect_success_total 6121
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 6178
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2695
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3401
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 122
telemt_me_reconnect_attempts_total 5108
telemt_me_reconnect_success_total 5091
telemt_me_reader_eof_total 5466
telemt_me_idle_close_by_peer_total 5466
telemt_me_route_drop_no_conn_total 5453
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 14708
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 5131
telemt_me_writer_restored_same_endpoint_total 5075
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 40
telemt_user_connections_total{user="hello"} 14708
telemt_user_connections_current{user="hello"} 44
telemt_user_octets_from_client{user="hello"} 102556552 (97.81 MB)
telemt_user_octets_to_client{user="hello"} 6885191896 (6.41 GB)
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 9
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 69916.2 (19h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 370304
telemt_connections_bad_total 6633
telemt_handshake_timeouts_total 2856
telemt_upstream_connect_attempt_total 14902
telemt_upstream_connect_success_total 14818
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 14902
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6919
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7876
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 1356
telemt_me_reconnect_attempts_total 14960
telemt_me_reconnect_success_total 11339
telemt_me_reader_eof_total 12174
telemt_me_idle_close_by_peer_total 12171
telemt_me_route_drop_no_conn_total 165933
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 362045
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 314
telemt_desync_full_logged_total 123
telemt_desync_suppressed_total 191
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 116
telemt_desync_frames_bucket_total{bucket="gt_10"} 123
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 11592
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 11332
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 253
telemt_user_connections_total{user="hello"} 350291
telemt_user_connections_current{user="hello"} 247
telemt_user_octets_from_client{user="hello"} 5921633912 (5.51 GB)
telemt_user_octets_to_client{user="hello"} 212392770888 (197.81 GB)
telemt_user_unique_ips_current{user="hello"} 93
telemt_user_unique_ips_recent_window{user="hello"} 26
```