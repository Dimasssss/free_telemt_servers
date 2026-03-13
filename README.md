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

# Server Metrics 2026-03-13 05:10:07 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 77803.2 (21h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 295906
telemt_connections_bad_total 3064
telemt_handshake_timeouts_total 5980
telemt_upstream_connect_attempt_total 19653
telemt_upstream_connect_success_total 19561
telemt_upstream_connect_fail_total 92
telemt_upstream_connect_attempts_per_request{bucket="1"} 19653
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8760
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10753
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 48
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 92
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 1560
telemt_me_reconnect_attempts_total 19142
telemt_me_reconnect_success_total 15645
telemt_me_reader_eof_total 16730
telemt_me_idle_close_by_peer_total 16729
telemt_me_route_drop_no_conn_total 92214
telemt_me_route_drop_channel_closed_total 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248828
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 848
telemt_desync_full_logged_total 316
telemt_desync_suppressed_total 532
telemt_desync_frames_bucket_total{bucket="1_2"} 169
telemt_desync_frames_bucket_total{bucket="3_10"} 310
telemt_desync_frames_bucket_total{bucket="gt_10"} 369
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 15923
telemt_me_refill_failed_total 106
telemt_me_writer_restored_same_endpoint_total 15629
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 278
telemt_user_connections_total{user="hello"} 248767
telemt_user_connections_current{user="hello"} 269
telemt_user_octets_from_client{user="hello"} 4275694120 (3.98 GB)
telemt_user_octets_to_client{user="hello"} 121575208764 (113.23 GB)
telemt_user_unique_ips_current{user="hello"} 80
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 77696.1 (21h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 135566
telemt_connections_bad_total 759
telemt_handshake_timeouts_total 1016
telemt_upstream_connect_attempt_total 41547
telemt_upstream_connect_success_total 41028
telemt_upstream_connect_fail_total 519
telemt_upstream_connect_attempts_per_request{bucket="1"} 41547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24490
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16030
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 508
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 519
telemt_me_keepalive_timeout_total 583
telemt_me_reconnect_attempts_total 67193
telemt_me_reconnect_success_total 20630
telemt_me_reader_eof_total 22732
telemt_me_idle_close_by_peer_total 22732
telemt_me_route_drop_no_conn_total 50291
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 112279
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 16
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
telemt_pool_swap_total 23
telemt_me_writer_removed_unexpected_total 22247
telemt_me_refill_failed_total 1453
telemt_me_writer_restored_same_endpoint_total 20615
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 1617
telemt_user_connections_total{user="hello"} 128779
telemt_user_connections_current{user="hello"} 105
telemt_user_octets_from_client{user="hello"} 1337957976 (1.25 GB)
telemt_user_octets_to_client{user="hello"} 39118569279 (36.43 GB)
telemt_user_msgs_from_client{user="hello"} 257002
telemt_user_msgs_to_client{user="hello"} 2006834
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 11
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 77659.5 (21h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 163764
telemt_connections_bad_total 1859
telemt_handshake_timeouts_total 2644
telemt_upstream_connect_attempt_total 21455
telemt_upstream_connect_success_total 21453
telemt_upstream_connect_fail_total 2
telemt_upstream_connect_attempts_per_request{bucket="1"} 21455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9883
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11547
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2
telemt_me_keepalive_timeout_total 460
telemt_me_reconnect_attempts_total 18682
telemt_me_reconnect_success_total 17517
telemt_me_reader_eof_total 18768
telemt_me_idle_close_by_peer_total 18768
telemt_me_route_drop_no_conn_total 63597
telemt_me_route_drop_channel_closed_total 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 153211
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
telemt_pool_swap_total 70
telemt_me_writer_removed_unexpected_total 17707
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 17497
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 190
telemt_user_connections_total{user="hello"} 153138
telemt_user_connections_current{user="hello"} 99
telemt_user_octets_from_client{user="hello"} 2900964132 (2.70 GB)
telemt_user_octets_to_client{user="hello"} 70849150248 (65.98 GB)
telemt_user_unique_ips_current{user="hello"} 37
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 77635.3 (21h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 236738
telemt_connections_bad_total 13564
telemt_handshake_timeouts_total 1773
telemt_upstream_connect_attempt_total 33782
telemt_upstream_connect_success_total 23890
telemt_upstream_connect_fail_total 9892
telemt_upstream_connect_attempts_per_request{bucket="1"} 33782
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12031
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11683
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 168
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9892
telemt_me_keepalive_timeout_total 3314
telemt_me_reconnect_attempts_total 67288
telemt_me_reconnect_success_total 17134
telemt_me_reader_eof_total 19224
telemt_me_idle_close_by_peer_total 19217
telemt_me_route_drop_no_conn_total 86036
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 198165
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 17
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 555
telemt_desync_full_logged_total 153
telemt_desync_suppressed_total 402
telemt_desync_frames_bucket_total{bucket="1_2"} 140
telemt_desync_frames_bucket_total{bucket="3_10"} 205
telemt_desync_frames_bucket_total{bucket="gt_10"} 210
telemt_pool_swap_total 21
telemt_me_writer_removed_unexpected_total 18925
telemt_me_refill_failed_total 1563
telemt_me_writer_restored_same_endpoint_total 17124
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 1791
telemt_user_connections_total{user="hello"} 200909
telemt_user_connections_current{user="hello"} 164
telemt_user_octets_from_client{user="hello"} 3273008446 (3.05 GB)
telemt_user_octets_to_client{user="hello"} 80528058757 (75.00 GB)
telemt_user_msgs_from_client{user="hello"} 67768
telemt_user_msgs_to_client{user="hello"} 112762
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 13
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 27807.0 (7h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 29138
telemt_connections_bad_total 5232
telemt_handshake_timeouts_total 128
telemt_upstream_connect_attempt_total 9046
telemt_upstream_connect_success_total 8960
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 9046
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3921
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5007
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 32
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_timeout_total 215
telemt_me_reconnect_attempts_total 7601
telemt_me_reconnect_success_total 7572
telemt_me_reader_eof_total 8060
telemt_me_idle_close_by_peer_total 8060
telemt_me_route_drop_no_conn_total 8037
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 22976
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 25
telemt_me_writer_removed_unexpected_total 7641
telemt_me_writer_restored_same_endpoint_total 7554
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 22976
telemt_user_connections_current{user="hello"} 61
telemt_user_octets_from_client{user="hello"} 155633752 (148.42 MB)
telemt_user_octets_to_client{user="hello"} 9309201240 (8.67 GB)
telemt_user_unique_ips_current{user="hello"} 28
telemt_user_unique_ips_recent_window{user="hello"} 10
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 77592.0 (21h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 397677
telemt_connections_bad_total 7734
telemt_handshake_timeouts_total 2961
telemt_upstream_connect_attempt_total 16539
telemt_upstream_connect_success_total 16446
telemt_upstream_connect_fail_total 93
telemt_upstream_connect_attempts_per_request{bucket="1"} 16539
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7662
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8759
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 93
telemt_me_keepalive_timeout_total 1447
telemt_me_reconnect_attempts_total 16200
telemt_me_reconnect_success_total 12570
telemt_me_reader_eof_total 13502
telemt_me_idle_close_by_peer_total 13499
telemt_me_route_drop_no_conn_total 177397
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 387417
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 331
telemt_desync_full_logged_total 125
telemt_desync_suppressed_total 206
telemt_desync_frames_bucket_total{bucket="1_2"} 77
telemt_desync_frames_bucket_total{bucket="3_10"} 121
telemt_desync_frames_bucket_total{bucket="gt_10"} 133
telemt_pool_swap_total 72
telemt_me_writer_removed_unexpected_total 12845
telemt_me_refill_failed_total 111
telemt_me_writer_restored_same_endpoint_total 12563
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 275
telemt_user_connections_total{user="hello"} 375660
telemt_user_connections_current{user="hello"} 306
telemt_user_octets_from_client{user="hello"} 6228207336 (5.80 GB)
telemt_user_octets_to_client{user="hello"} 220935629404 (205.76 GB)
telemt_user_unique_ips_current{user="hello"} 117
telemt_user_unique_ips_recent_window{user="hello"} 39
```