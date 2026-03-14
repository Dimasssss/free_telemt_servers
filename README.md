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

# Server Metrics 2026-03-14 20:43:35 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.17

telemt_uptime_seconds 26835.0 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 136355
telemt_connections_bad_total 16130
telemt_handshake_timeouts_total 1448
telemt_upstream_connect_attempt_total 6008
telemt_upstream_connect_success_total 6006
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 6008
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3071
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 83
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 216
telemt_me_reconnect_attempts_total 4674
telemt_me_reconnect_success_total 4638
telemt_me_reader_eof_total 4920
telemt_me_idle_close_by_peer_total 4920
telemt_me_route_drop_no_conn_total 49350
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112632
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 505
telemt_desync_full_logged_total 181
telemt_desync_suppressed_total 324
telemt_desync_frames_bucket_total{bucket="1_2"} 119
telemt_desync_frames_bucket_total{bucket="3_10"} 183
telemt_desync_frames_bucket_total{bucket="gt_10"} 203
telemt_pool_swap_total 24
telemt_me_writer_removed_unexpected_total 4718
telemt_me_writer_restored_same_endpoint_total 4620
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 72
telemt_me_writer_removed_unexpected_minus_restored_total 80
telemt_user_connections_total{user="hello"} 112552
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 2407106348 (2.24 GB)
telemt_user_octets_to_client{user="hello"} 67663157744 (63.02 GB)
telemt_user_unique_ips_current{user="hello"} 85
telemt_user_unique_ips_recent_window{user="hello"} 34
```

## psb.hosting

```
telemt 3.3.17

telemt_uptime_seconds 26833.2 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 55860
telemt_connections_bad_total 729
telemt_handshake_timeouts_total 977
telemt_upstream_connect_attempt_total 6967
telemt_upstream_connect_success_total 6923
telemt_upstream_connect_fail_total 44
telemt_upstream_connect_attempts_per_request{bucket="1"} 6967
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3956
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 44
telemt_me_keepalive_timeout_total 130
telemt_me_reconnect_attempts_total 8131
telemt_me_reconnect_success_total 5552
telemt_me_reader_eof_total 5897
telemt_me_idle_close_by_peer_total 5897
telemt_me_route_drop_no_conn_total 29057
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 51976
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 18
telemt_me_writer_removed_unexpected_total 5709
telemt_me_refill_failed_total 79
telemt_me_writer_restored_same_endpoint_total 5547
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 120
telemt_me_writer_removed_unexpected_minus_restored_total 157
telemt_user_connections_total{user="hello"} 51966
telemt_user_connections_current{user="hello"} 178
telemt_user_octets_from_client{user="hello"} 1332808572 (1.24 GB)
telemt_user_octets_to_client{user="hello"} 22699593812 (21.14 GB)
telemt_user_unique_ips_current{user="hello"} 41
telemt_user_unique_ips_recent_window{user="hello"} 12
```

## koara.io

```
telemt 3.3.17

telemt_uptime_seconds 26837.8 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 62577
telemt_connections_bad_total 391
telemt_handshake_timeouts_total 1888
telemt_upstream_connect_attempt_total 8853
telemt_upstream_connect_success_total 8763
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 8853
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4103
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4650
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 249
telemt_me_reconnect_attempts_total 104940
telemt_me_reconnect_success_total 7075
telemt_me_reader_eof_total 7556
telemt_me_idle_close_by_peer_total 7556
telemt_me_route_drop_no_conn_total 23676
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 57042
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 15
telemt_desync_full_logged_total 4
telemt_desync_suppressed_total 11
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 5
telemt_desync_frames_bucket_total{bucket="gt_10"} 6
telemt_pool_swap_total 17
telemt_me_writer_removed_unexpected_total 7354
telemt_me_refill_failed_total 3169
telemt_me_writer_restored_same_endpoint_total 7029
telemt_me_writer_restored_fallback_total 46
telemt_me_async_recovery_trigger_total 1685
telemt_me_writer_removed_unexpected_minus_restored_total 279
telemt_user_connections_total{user="hello"} 57109
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 3841467629 (3.58 GB)
telemt_user_octets_to_client{user="hello"} 41061324166 (38.24 GB)
telemt_user_msgs_from_client{user="hello"} 3762
telemt_user_msgs_to_client{user="hello"} 18362
telemt_user_unique_ips_current{user="hello"} 44
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## landvps.ru

```
telemt 3.3.17

telemt_uptime_seconds 26842.4 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 79941
telemt_connections_bad_total 206
telemt_handshake_timeouts_total 594
telemt_upstream_connect_attempt_total 6596
telemt_upstream_connect_success_total 6556
telemt_upstream_connect_fail_total 40
telemt_upstream_connect_attempts_per_request{bucket="1"} 6596
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3068
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3460
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 40
telemt_me_keepalive_timeout_total 190
telemt_me_reconnect_attempts_total 5049
telemt_me_reconnect_success_total 5023
telemt_me_reader_eof_total 5282
telemt_me_idle_close_by_peer_total 5282
telemt_me_route_drop_no_conn_total 34483
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 75707
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 609
telemt_desync_full_logged_total 154
telemt_desync_suppressed_total 455
telemt_desync_frames_bucket_total{bucket="1_2"} 106
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 245
telemt_pool_swap_total 22
telemt_me_writer_removed_unexpected_total 5078
telemt_me_writer_restored_same_endpoint_total 5021
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 60
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 75754
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 1231965204 (1.15 GB)
telemt_user_octets_to_client{user="hello"} 26289595406 (24.48 GB)
telemt_user_msgs_from_client{user="hello"} 473
telemt_user_msgs_to_client{user="hello"} 2783
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## rdp-onedash.ru

```
telemt 3.3.17

telemt_uptime_seconds 26835.5 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 58530
telemt_connections_bad_total 5160
telemt_handshake_timeouts_total 3324
telemt_upstream_connect_attempt_total 6384
telemt_upstream_connect_success_total 6313
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 6384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2834
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3439
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 192
telemt_me_reconnect_attempts_total 11475
telemt_me_reconnect_success_total 4939
telemt_me_reader_eof_total 5362
telemt_me_idle_close_by_peer_total 5362
telemt_me_route_drop_no_conn_total 19340
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 47280
telemt_me_writer_pick_total{mode="p2c",result="full"} 2
telemt_me_writer_pick_total{mode="p2c",result="closed"} 13
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 262
telemt_desync_full_logged_total 39
telemt_desync_suppressed_total 223
telemt_desync_frames_bucket_total{bucket="1_2"} 37
telemt_desync_frames_bucket_total{bucket="3_10"} 92
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 5188
telemt_me_refill_failed_total 203
telemt_me_writer_restored_same_endpoint_total 4935
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 47267
telemt_user_connections_current{user="hello"} 72
telemt_user_octets_from_client{user="hello"} 1377238688 (1.28 GB)
telemt_user_octets_to_client{user="hello"} 28839729412 (26.86 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## hostvds.com

```
telemt 3.3.17

telemt_uptime_seconds 26835.1 (7h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 201830
telemt_connections_bad_total 7295
telemt_handshake_timeouts_total 2653
telemt_upstream_connect_attempt_total 5227
telemt_upstream_connect_success_total 5132
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 5227
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2629
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_timeout_total 252
telemt_me_reconnect_attempts_total 8771
telemt_me_reconnect_success_total 3764
telemt_me_reader_eof_total 4084
telemt_me_idle_close_by_peer_total 4084
telemt_me_route_drop_no_conn_total 112998
telemt_me_route_drop_channel_closed_total 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 185959
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 11
telemt_me_endpoint_quarantine_total 4
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 55
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 35
telemt_desync_frames_bucket_total{bucket="1_2"} 20
telemt_desync_frames_bucket_total{bucket="3_10"} 15
telemt_desync_frames_bucket_total{bucket="gt_10"} 20
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 3966
telemt_me_refill_failed_total 155
telemt_me_writer_restored_same_endpoint_total 3760
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 182446
telemt_user_connections_current{user="hello"} 456
telemt_user_octets_from_client{user="hello"} 3941458096 (3.67 GB)
telemt_user_octets_to_client{user="hello"} 95713241440 (89.14 GB)
telemt_user_unique_ips_current{user="hello"} 161
telemt_user_unique_ips_recent_window{user="hello"} 49
```