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

# Server Metrics 2026-03-13 01:30:05 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 64601.9 (17h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 263768
telemt_connections_bad_total 2766
telemt_handshake_timeouts_total 5611
telemt_upstream_connect_attempt_total 16325
telemt_upstream_connect_success_total 16254
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 16325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9025
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1510
telemt_me_reconnect_attempts_total 16479
telemt_me_reconnect_success_total 13003
telemt_me_reader_eof_total 13873
telemt_me_idle_close_by_peer_total 13872
telemt_me_route_drop_no_conn_total 82183
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 218661
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 728
telemt_desync_full_logged_total 274
telemt_desync_suppressed_total 454
telemt_desync_frames_bucket_total{bucket="1_2"} 129
telemt_desync_frames_bucket_total{bucket="3_10"} 271
telemt_desync_frames_bucket_total{bucket="gt_10"} 328
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 13252
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 12987
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 218429
telemt_user_connections_current{user="hello"} 204
telemt_user_octets_from_client{user="hello"} 3945952888 (3.67 GB)
telemt_user_octets_to_client{user="hello"} 109760856048 (102.22 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 17
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 64494.9 (17h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 122714
telemt_connections_bad_total 733
telemt_handshake_timeouts_total 974
telemt_upstream_connect_attempt_total 36095
telemt_upstream_connect_success_total 35654
telemt_upstream_connect_fail_total 441
telemt_upstream_connect_attempts_per_request{bucket="1"} 36095
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 22362
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 501
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 441
telemt_me_keepalive_timeout_total 460
telemt_me_reconnect_attempts_total 60132
telemt_me_reconnect_success_total 15920
telemt_me_reader_eof_total 17724
telemt_me_idle_close_by_peer_total 17724
telemt_me_route_drop_no_conn_total 43699
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99985
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
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 17416
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 15905
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1496
telemt_user_connections_total{user="hello"} 116485
telemt_user_connections_current{user="hello"} 102
telemt_user_octets_from_client{user="hello"} 1247903912 (1.16 GB)
telemt_user_octets_to_client{user="hello"} 35179807883 (32.76 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 64458.6 (17h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 147986
telemt_connections_bad_total 1688
telemt_handshake_timeouts_total 2339
telemt_upstream_connect_attempt_total 17785
telemt_upstream_connect_success_total 17783
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 17785
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8273
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9489
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 367
telemt_me_reconnect_attempts_total 15664
telemt_me_reconnect_success_total 14508
telemt_me_reader_eof_total 15507
telemt_me_idle_close_by_peer_total 15507
telemt_me_route_drop_no_conn_total 56391
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 138404
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
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 14672
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 14488
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 138368
telemt_user_connections_current{user="hello"} 58
telemt_user_octets_from_client{user="hello"} 2639242812 (2.46 GB)
telemt_user_octets_to_client{user="hello"} 63740493000 (59.36 GB)
telemt_user_unique_ips_current{user="hello"} 29
telemt_user_unique_ips_recent_window{user="hello"} 8
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 64434.0 (17h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 211469
telemt_connections_bad_total 13302
telemt_handshake_timeouts_total 1426
telemt_upstream_connect_attempt_total 29832
telemt_upstream_connect_success_total 20064
telemt_upstream_connect_fail_total 9768
telemt_upstream_connect_attempts_per_request{bucket="1"} 29832
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10265
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9639
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9768
telemt_me_keepalive_timeout_total 3216
telemt_me_reconnect_attempts_total 50861
telemt_me_reconnect_success_total 13963
telemt_me_reader_eof_total 15613
telemt_me_idle_close_by_peer_total 15606
telemt_me_route_drop_no_conn_total 76084
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 175201
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 13
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
telemt_me_writer_removed_unexpected_total 15321
telemt_me_refill_failed_total 1149
telemt_me_writer_restored_same_endpoint_total 13953
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1358
telemt_user_connections_total{user="hello"} 177953
telemt_user_connections_current{user="hello"} 115
telemt_user_octets_from_client{user="hello"} 3030084710 (2.82 GB)
telemt_user_octets_to_client{user="hello"} 73063397481 (68.05 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 14605.7 (4h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13009
telemt_connections_bad_total 2764
telemt_handshake_timeouts_total 23
telemt_upstream_connect_attempt_total 4573
telemt_upstream_connect_success_total 4533
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 4573
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2012
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2503
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 18
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 93
telemt_me_reconnect_attempts_total 3777
telemt_me_reconnect_success_total 3768
telemt_me_reader_eof_total 4030
telemt_me_idle_close_by_peer_total 4030
telemt_me_route_drop_no_conn_total 4064
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 9830
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 3789
telemt_me_writer_restored_same_endpoint_total 3752
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 21
telemt_user_connections_total{user="hello"} 9830
telemt_user_connections_current{user="hello"} 35
telemt_user_octets_from_client{user="hello"} 38390792 (36.61 MB)
telemt_user_octets_to_client{user="hello"} 2823467164 (2.63 GB)
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 5
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 64390.5 (17h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 355059
telemt_connections_bad_total 6545
telemt_handshake_timeouts_total 2605
telemt_upstream_connect_attempt_total 13652
telemt_upstream_connect_success_total 13579
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 13652
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6356
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7203
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 1341
telemt_me_reconnect_attempts_total 13982
telemt_me_reconnect_success_total 10364
telemt_me_reader_eof_total 11123
telemt_me_idle_close_by_peer_total 11121
telemt_me_route_drop_no_conn_total 158598
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 347382
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 301
telemt_desync_full_logged_total 118
telemt_desync_suppressed_total 183
telemt_desync_frames_bucket_total{bucket="1_2"} 75
telemt_desync_frames_bucket_total{bucket="3_10"} 112
telemt_desync_frames_bucket_total{bucket="gt_10"} 114
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10604
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 10357
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 240
telemt_user_connections_total{user="hello"} 335683
telemt_user_connections_current{user="hello"} 233
telemt_user_octets_from_client{user="hello"} 5692062736 (5.30 GB)
telemt_user_octets_to_client{user="hello"} 181659053680 (169.18 GB)
telemt_user_unique_ips_current{user="hello"} 87
telemt_user_unique_ips_recent_window{user="hello"} 22
```