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

# Server Metrics 2026-03-12 17:04:09 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 34246.0 (9h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 179659
telemt_connections_bad_total 2388
telemt_handshake_timeouts_total 4900
telemt_upstream_connect_attempt_total 8530
telemt_upstream_connect_success_total 8497
telemt_upstream_connect_fail_total 32
telemt_upstream_connect_attempts_per_request{bucket="1"} 8529
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3764
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4725
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 32
telemt_me_keepalive_timeout_total 343
telemt_me_reconnect_attempts_total 7873
telemt_me_reconnect_success_total 6734
telemt_me_reader_eof_total 7100
telemt_me_idle_close_by_peer_total 7099
telemt_me_route_drop_no_conn_total 52415
telemt_me_route_drop_channel_closed_total 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 152988
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
telemt_me_writer_removed_unexpected_total 6839
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 6718
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 152947
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 2655437432 (2.47 GB)
telemt_user_octets_to_client{user="hello"} 62550600864 (58.25 GB)
telemt_user_unique_ips_current{user="hello"} 101
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 34138.5 (9h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75629
telemt_connections_bad_total 467
telemt_handshake_timeouts_total 636
telemt_upstream_connect_attempt_total 10732
telemt_upstream_connect_success_total 10510
telemt_upstream_connect_fail_total 222
telemt_upstream_connect_attempts_per_request{bucket="1"} 10732
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4193
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6235
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 82
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 222
telemt_me_keepalive_timeout_total 291
telemt_me_reconnect_attempts_total 33275
telemt_me_reconnect_success_total 8795
telemt_me_reader_eof_total 9727
telemt_me_idle_close_by_peer_total 9727
telemt_me_route_drop_no_conn_total 33163
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71819
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
telemt_me_writer_removed_unexpected_total 9626
telemt_me_refill_failed_total 764
telemt_me_writer_restored_same_endpoint_total 8780
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 831
telemt_user_connections_total{user="hello"} 71804
telemt_user_connections_current{user="hello"} 110
telemt_user_octets_from_client{user="hello"} 793989292 (757.21 MB)
telemt_user_octets_to_client{user="hello"} 19989672620 (18.62 GB)
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 34102.1 (9h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 101913
telemt_connections_bad_total 1494
telemt_handshake_timeouts_total 2059
telemt_upstream_connect_attempt_total 9440
telemt_upstream_connect_success_total 9440
telemt_upstream_connect_attempts_per_request{bucket="1"} 9440
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4568
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4862
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 189
telemt_me_reconnect_attempts_total 7737
telemt_me_reconnect_success_total 7667
telemt_me_reader_eof_total 8117
telemt_me_idle_close_by_peer_total 8117
telemt_me_route_drop_no_conn_total 37825
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 94182
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 17
telemt_desync_frames_bucket_total{bucket="1_2"} 1
telemt_desync_frames_bucket_total{bucket="3_10"} 10
telemt_desync_frames_bucket_total{bucket="gt_10"} 22
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7738
telemt_me_writer_restored_same_endpoint_total 7647
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 94156
telemt_user_connections_current{user="hello"} 134
telemt_user_octets_from_client{user="hello"} 2275776928 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 48681666276 (45.34 GB)
telemt_user_unique_ips_current{user="hello"} 61
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 34077.7 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 140010
telemt_connections_bad_total 13066
telemt_handshake_timeouts_total 1062
telemt_upstream_connect_attempt_total 7377
telemt_upstream_connect_success_total 7144
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 7377
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3319
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3798
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 27
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 349
telemt_me_reconnect_attempts_total 33502
telemt_me_reconnect_success_total 5416
telemt_me_reader_eof_total 6426
telemt_me_idle_close_by_peer_total 6426
telemt_me_route_drop_no_conn_total 50259
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 118775
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 7
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
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 6355
telemt_me_refill_failed_total 876
telemt_me_writer_restored_same_endpoint_total 5408
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 121
telemt_me_writer_removed_unexpected_minus_restored_total 939
telemt_user_connections_total{user="hello"} 118657
telemt_user_connections_current{user="hello"} 188
telemt_user_octets_from_client{user="hello"} 2166727708 (2.02 GB)
telemt_user_octets_to_client{user="hello"} 50984086328 (47.48 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 34047.2 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83821
telemt_connections_bad_total 9001
telemt_handshake_timeouts_total 1132
telemt_upstream_connect_attempt_total 42899
telemt_upstream_connect_success_total 42482
telemt_upstream_connect_fail_total 417
telemt_upstream_connect_attempts_per_request{bucket="1"} 42899
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36280
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6163
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 39
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 417
telemt_me_keepalive_timeout_total 137
telemt_me_reconnect_attempts_total 46565
telemt_me_reconnect_success_total 3700
telemt_me_reader_eof_total 5034
telemt_me_idle_close_by_peer_total 5034
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 13082
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 34681
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
telemt_me_writer_removed_unexpected_total 5062
telemt_me_refill_failed_total 1342
telemt_me_writer_restored_same_endpoint_total 3683
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 18
telemt_me_writer_removed_unexpected_minus_restored_total 1362
telemt_user_connections_total{user="hello"} 71734
telemt_user_connections_current{user="hello"} 150
telemt_user_octets_from_client{user="hello"} 666395667 (635.52 MB)
telemt_user_octets_to_client{user="hello"} 21416924176 (19.95 GB)
telemt_user_msgs_from_client{user="hello"} 593639
telemt_user_msgs_to_client{user="hello"} 2192517
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 34034.6 (9h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 216034
telemt_connections_bad_total 973
telemt_handshake_timeouts_total 1734
telemt_upstream_connect_attempt_total 7317
telemt_upstream_connect_success_total 7280
telemt_upstream_connect_fail_total 37
telemt_upstream_connect_attempts_per_request{bucket="1"} 7317
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3404
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3866
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 37
telemt_me_keepalive_timeout_total 412
telemt_me_reconnect_attempts_total 6624
telemt_me_reconnect_success_total 5554
telemt_me_reader_eof_total 5850
telemt_me_idle_close_by_peer_total 5849
telemt_me_route_drop_no_conn_total 98373
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 216322
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 253
telemt_desync_full_logged_total 100
telemt_desync_suppressed_total 153
telemt_desync_frames_bucket_total{bucket="1_2"} 66
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 5659
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 5547
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 105
telemt_user_connections_total{user="hello"} 206258
telemt_user_connections_current{user="hello"} 507
telemt_user_octets_from_client{user="hello"} 3794168076 (3.53 GB)
telemt_user_octets_to_client{user="hello"} 94925820832 (88.41 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 67
```