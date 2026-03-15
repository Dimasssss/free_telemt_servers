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

# Server Metrics 2026-03-15 12:09:58 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 50130.1 (13h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217800
telemt_connections_bad_total 1489
telemt_handshake_timeouts_total 4626
telemt_upstream_connect_attempt_total 12701
telemt_upstream_connect_success_total 12632
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 12701
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5594
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7025
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 13496
telemt_me_reconnect_success_total 10125
telemt_me_reader_eof_total 10825
telemt_me_idle_close_by_peer_total 10825
telemt_me_route_drop_no_conn_total 423944
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 264359
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1506
telemt_desync_full_logged_total 600
telemt_desync_suppressed_total 906
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 600
telemt_desync_frames_bucket_total{bucket="gt_10"} 659
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 10330
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10094
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 203470
telemt_user_connections_current{user="hello"} 370
telemt_user_octets_from_client{user="hello"} 3823283340 (3.56 GB)
telemt_user_octets_to_client{user="hello"} 191723636660 (178.56 GB)
telemt_user_unique_ips_current{user="hello"} 116
telemt_user_unique_ips_recent_window{user="hello"} 52
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 50137.0 (13h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 75812
telemt_connections_bad_total 2367
telemt_handshake_timeouts_total 5269
telemt_upstream_connect_attempt_total 13637
telemt_upstream_connect_success_total 13637
telemt_upstream_connect_attempts_per_request{bucket="1"} 13637
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5842
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7690
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 105
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 13439
telemt_me_reconnect_success_total 11105
telemt_me_reader_eof_total 11907
telemt_me_idle_close_by_peer_total 11907
telemt_me_route_drop_no_conn_total 34460
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 65702
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 11296
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 11089
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 191
telemt_user_connections_total{user="hello"} 65702
telemt_user_connections_current{user="hello"} 239
telemt_user_octets_from_client{user="hello"} 1187333444 (1.11 GB)
telemt_user_octets_to_client{user="hello"} 28950696512 (26.96 GB)
telemt_user_unique_ips_current{user="hello"} 49
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 50129.1 (13h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 80440
telemt_connections_bad_total 1020
telemt_handshake_timeouts_total 2578
telemt_upstream_connect_attempt_total 14363
telemt_upstream_connect_success_total 14355
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 14363
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6244
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 13965
telemt_me_reconnect_success_total 11822
telemt_me_reader_eof_total 12659
telemt_me_idle_close_by_peer_total 12659
telemt_me_route_drop_no_conn_total 30738
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 73306
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 45
telemt_desync_full_logged_total 16
telemt_desync_suppressed_total 29
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 22
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 12002
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 11814
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 180
telemt_user_connections_total{user="hello"} 73222
telemt_user_connections_current{user="hello"} 144
telemt_user_octets_from_client{user="hello"} 9541316528 (8.89 GB)
telemt_user_octets_to_client{user="hello"} 44220384912 (41.18 GB)
telemt_user_unique_ips_current{user="hello"} 58
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 50128.9 (13h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 109212
telemt_connections_bad_total 368
telemt_handshake_timeouts_total 705
telemt_upstream_connect_attempt_total 11764
telemt_upstream_connect_success_total 11763
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 11764
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6102
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 38
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9312
telemt_me_reconnect_success_total 9264
telemt_me_reader_eof_total 9885
telemt_me_idle_close_by_peer_total 9885
telemt_me_route_drop_no_conn_total 43575
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 99633
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 266
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 186
telemt_desync_frames_bucket_total{bucket="1_2"} 62
telemt_desync_frames_bucket_total{bucket="3_10"} 113
telemt_desync_frames_bucket_total{bucket="gt_10"} 91
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 9364
telemt_me_writer_restored_same_endpoint_total 9253
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 100
telemt_user_connections_total{user="hello"} 99554
telemt_user_connections_current{user="hello"} 200
telemt_user_octets_from_client{user="hello"} 1769033780 (1.65 GB)
telemt_user_octets_to_client{user="hello"} 55415901948 (51.61 GB)
telemt_user_unique_ips_current{user="hello"} 73
telemt_user_unique_ips_recent_window{user="hello"} 32
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 25200.3 (7h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 57754
telemt_connections_bad_total 15214
telemt_handshake_timeouts_total 854
telemt_upstream_connect_attempt_total 8198
telemt_upstream_connect_success_total 8139
telemt_upstream_connect_fail_total 59
telemt_upstream_connect_attempts_per_request{bucket="1"} 8198
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4454
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 59
telemt_me_reconnect_attempts_total 101128
telemt_me_reconnect_success_total 6711
telemt_me_reader_eof_total 6980
telemt_me_idle_close_by_peer_total 6980
telemt_me_route_drop_no_conn_total 20302
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 40375
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 96
telemt_desync_full_logged_total 18
telemt_desync_suppressed_total 78
telemt_desync_frames_bucket_total{bucket="1_2"} 14
telemt_desync_frames_bucket_total{bucket="3_10"} 39
telemt_desync_frames_bucket_total{bucket="gt_10"} 43
telemt_pool_swap_total 16
telemt_me_writer_removed_unexpected_total 6699
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 6607
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 40512
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 602371161 (574.47 MB)
telemt_user_octets_to_client{user="hello"} 15618198507 (14.55 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 42
telemt_user_unique_ips_recent_window{user="hello"} 22
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 50128.1 (13h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 285945
telemt_connections_bad_total 47694
telemt_handshake_timeouts_total 2081
telemt_upstream_connect_attempt_total 10603
telemt_upstream_connect_success_total 10539
telemt_upstream_connect_fail_total 64
telemt_upstream_connect_attempts_per_request{bucket="1"} 10603
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5276
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5260
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 64
telemt_me_reconnect_attempts_total 8077
telemt_me_reconnect_success_total 8025
telemt_me_reader_eof_total 8548
telemt_me_idle_close_by_peer_total 8548
telemt_me_route_drop_no_conn_total 126824
telemt_me_route_drop_channel_closed_total 28
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227831
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 141
telemt_desync_full_logged_total 59
telemt_desync_suppressed_total 82
telemt_desync_frames_bucket_total{bucket="1_2"} 44
telemt_desync_frames_bucket_total{bucket="3_10"} 58
telemt_desync_frames_bucket_total{bucket="gt_10"} 39
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8094
telemt_me_writer_restored_same_endpoint_total 7998
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 226192
telemt_user_connections_current{user="hello"} 607
telemt_user_octets_from_client{user="hello"} 4907199716 (4.57 GB)
telemt_user_octets_to_client{user="hello"} 109853190804 (102.31 GB)
telemt_user_unique_ips_current{user="hello"} 226
telemt_user_unique_ips_recent_window{user="hello"} 72
```