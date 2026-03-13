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

# Server Metrics 2026-03-13 02:41:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 68899.4 (19h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 272798
telemt_connections_bad_total 2859
telemt_handshake_timeouts_total 5647
telemt_upstream_connect_attempt_total 17468
telemt_upstream_connect_success_total 17391
telemt_upstream_connect_fail_total 77
telemt_upstream_connect_attempts_per_request{bucket="1"} 17468
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7701
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9644
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 77
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1521
telemt_me_reconnect_attempts_total 17401
telemt_me_reconnect_success_total 13918
telemt_me_reader_eof_total 14868
telemt_me_idle_close_by_peer_total 14867
telemt_me_route_drop_no_conn_total 84964
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227219
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 748
telemt_desync_full_logged_total 281
telemt_desync_suppressed_total 467
telemt_desync_frames_bucket_total{bucket="1_2"} 139
telemt_desync_frames_bucket_total{bucket="3_10"} 276
telemt_desync_frames_bucket_total{bucket="gt_10"} 333
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 14177
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 13902
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 259
telemt_user_connections_total{user="hello"} 226985
telemt_user_connections_current{user="hello"} 235
telemt_user_octets_from_client{user="hello"} 4015474848 (3.74 GB)
telemt_user_octets_to_client{user="hello"} 111588529500 (103.92 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 19
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 68792.5 (19h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 126160
telemt_connections_bad_total 742
telemt_handshake_timeouts_total 982
telemt_upstream_connect_attempt_total 37872
telemt_upstream_connect_success_total 37408
telemt_upstream_connect_fail_total 464
telemt_upstream_connect_attempts_per_request{bucket="1"} 37872
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23080
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13826
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 502
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 464
telemt_me_keepalive_timeout_total 490
telemt_me_reconnect_attempts_total 61670
telemt_me_reconnect_success_total 17452
telemt_me_reader_eof_total 19321
telemt_me_idle_close_by_peer_total 19321
telemt_me_route_drop_no_conn_total 45423
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 103296
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
telemt_me_writer_removed_unexpected_total 18966
telemt_me_refill_failed_total 1380
telemt_me_writer_restored_same_endpoint_total 17437
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1514
telemt_user_connections_total{user="hello"} 119796
telemt_user_connections_current{user="hello"} 65
telemt_user_octets_from_client{user="hello"} 1263180400 (1.18 GB)
telemt_user_octets_to_client{user="hello"} 35598472891 (33.15 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 24
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 68755.9 (19h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 152020
telemt_connections_bad_total 1822
telemt_handshake_timeouts_total 2427
telemt_upstream_connect_attempt_total 19136
telemt_upstream_connect_success_total 19134
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 19136
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8844
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10268
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 382
telemt_me_reconnect_attempts_total 16796
telemt_me_reconnect_success_total 15636
telemt_me_reader_eof_total 16721
telemt_me_idle_close_by_peer_total 16721
telemt_me_route_drop_no_conn_total 58149
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142129
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
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 15807
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 15616
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 171
telemt_user_connections_total{user="hello"} 142063
telemt_user_connections_current{user="hello"} 75
telemt_user_octets_from_client{user="hello"} 2721391992 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 67170110116 (62.56 GB)
telemt_user_unique_ips_current{user="hello"} 30
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 68731.6 (19h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217622
telemt_connections_bad_total 13412
telemt_handshake_timeouts_total 1431
telemt_upstream_connect_attempt_total 31477
telemt_upstream_connect_success_total 21662
telemt_upstream_connect_fail_total 9815
telemt_upstream_connect_attempts_per_request{bucket="1"} 31477
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10937
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10557
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 160
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9815
telemt_me_keepalive_timeout_total 3275
telemt_me_reconnect_attempts_total 56211
telemt_me_reconnect_success_total 15343
telemt_me_reader_eof_total 17120
telemt_me_idle_close_by_peer_total 17113
telemt_me_route_drop_no_conn_total 79077
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 180876
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
telemt_me_writer_removed_unexpected_total 16832
telemt_me_refill_failed_total 1273
telemt_me_writer_restored_same_endpoint_total 15333
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1489
telemt_user_connections_total{user="hello"} 183627
telemt_user_connections_current{user="hello"} 131
telemt_user_octets_from_client{user="hello"} 3078041470 (2.87 GB)
telemt_user_octets_to_client{user="hello"} 75685286029 (70.49 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 36
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 18903.2 (5h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 17577
telemt_connections_bad_total 3555
telemt_handshake_timeouts_total 32
telemt_upstream_connect_attempt_total 5782
telemt_upstream_connect_success_total 5728
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 5782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2515
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3189
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_keepalive_timeout_total 113
telemt_me_reconnect_attempts_total 4801
telemt_me_reconnect_success_total 4784
telemt_me_reader_eof_total 5123
telemt_me_idle_close_by_peer_total 5123
telemt_me_route_drop_no_conn_total 5150
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 13485
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 15
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 4823
telemt_me_writer_restored_same_endpoint_total 4768
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 39
telemt_user_connections_total{user="hello"} 13485
telemt_user_connections_current{user="hello"} 54
telemt_user_octets_from_client{user="hello"} 87280592 (83.24 MB)
telemt_user_octets_to_client{user="hello"} 6607508852 (6.15 GB)
telemt_user_unique_ips_current{user="hello"} 27
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 68688.1 (19h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 366478
telemt_connections_bad_total 6623
telemt_handshake_timeouts_total 2848
telemt_upstream_connect_attempt_total 14668
telemt_upstream_connect_success_total 14584
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 14668
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6818
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7743
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_timeout_total 1352
telemt_me_reconnect_attempts_total 14769
telemt_me_reconnect_success_total 11148
telemt_me_reader_eof_total 11973
telemt_me_idle_close_by_peer_total 11971
telemt_me_route_drop_no_conn_total 164231
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358306
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
telemt_pool_swap_total 62
telemt_me_writer_removed_unexpected_total 11398
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 11141
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 250
telemt_user_connections_total{user="hello"} 346559
telemt_user_connections_current{user="hello"} 263
telemt_user_octets_from_client{user="hello"} 5864374020 (5.46 GB)
telemt_user_octets_to_client{user="hello"} 207833844744 (193.56 GB)
telemt_user_unique_ips_current{user="hello"} 97
telemt_user_unique_ips_recent_window{user="hello"} 25
```