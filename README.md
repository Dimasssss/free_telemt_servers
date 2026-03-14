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

# Server Metrics 2026-03-14 06:57:36 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 170655.8 (47h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 654774
telemt_connections_bad_total 32361
telemt_handshake_timeouts_total 13053
telemt_upstream_connect_attempt_total 43418
telemt_upstream_connect_success_total 43199
telemt_upstream_connect_fail_total 219
telemt_upstream_connect_attempts_per_request{bucket="1"} 43418
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23317
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 152
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 219
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5678
telemt_me_reconnect_attempts_total 39008
telemt_me_reconnect_success_total 34317
telemt_me_reader_eof_total 36700
telemt_me_idle_close_by_peer_total 36699
telemt_me_route_drop_no_conn_total 215769
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 556582
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2049
telemt_desync_full_logged_total 703
telemt_desync_suppressed_total 1346
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 748
telemt_desync_frames_bucket_total{bucket="gt_10"} 856
telemt_pool_swap_total 158
telemt_me_writer_removed_unexpected_total 34833
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 34297
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 516
telemt_user_connections_total{user="hello"} 556466
telemt_user_connections_current{user="hello"} 337
telemt_user_octets_from_client{user="hello"} 16310661858 (15.19 GB)
telemt_user_octets_to_client{user="hello"} 268599959884 (250.15 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 100
telemt_user_unique_ips_recent_window{user="hello"} 38
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 170548.8 (47h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 330183
telemt_connections_bad_total 2323
telemt_handshake_timeouts_total 2517
telemt_upstream_connect_attempt_total 150189
telemt_upstream_connect_success_total 148924
telemt_upstream_connect_fail_total 1265
telemt_upstream_connect_attempts_per_request{bucket="1"} 150189
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109852
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 36649
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2423
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1265
telemt_me_keepalive_timeout_total 4002
telemt_me_reconnect_attempts_total 177709
telemt_me_reconnect_success_total 37119
telemt_me_reader_eof_total 42492
telemt_me_idle_close_by_peer_total 42492
telemt_me_route_drop_no_conn_total 108112
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 209496
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 43
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 41859
telemt_me_refill_failed_total 4387
telemt_me_writer_restored_same_endpoint_total 37102
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4740
telemt_user_connections_total{user="hello"} 312604
telemt_user_connections_current{user="hello"} 139
telemt_user_octets_from_client{user="hello"} 3255453331 (3.03 GB)
telemt_user_octets_to_client{user="hello"} 101993711375 (94.99 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 39
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 170513.0 (47h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 385312
telemt_connections_bad_total 2970
telemt_handshake_timeouts_total 35080
telemt_upstream_connect_attempt_total 45006
telemt_upstream_connect_success_total 44997
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 45006
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20563
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24366
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3473
telemt_me_reconnect_attempts_total 37744
telemt_me_reconnect_success_total 36458
telemt_me_reader_eof_total 39208
telemt_me_idle_close_by_peer_total 39208
telemt_me_route_drop_no_conn_total 139162
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 333874
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 36898
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 36437
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 440
telemt_user_connections_total{user="hello"} 333645
telemt_user_connections_current{user="hello"} 132
telemt_user_octets_from_client{user="hello"} 13485612928 (12.56 GB)
telemt_user_octets_to_client{user="hello"} 131434537560 (122.41 GB)
telemt_user_unique_ips_current{user="hello"} 53
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 170488.1 (47h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487365
telemt_connections_bad_total 16239
telemt_handshake_timeouts_total 4524
telemt_upstream_connect_attempt_total 75385
telemt_upstream_connect_success_total 64806
telemt_upstream_connect_fail_total 10579
telemt_upstream_connect_attempts_per_request{bucket="1"} 75385
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 38249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26206
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 342
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10579
telemt_me_keepalive_timeout_total 5398
telemt_me_reconnect_attempts_total 143337
telemt_me_reconnect_success_total 37276
telemt_me_reader_eof_total 41789
telemt_me_idle_close_by_peer_total 41781
telemt_me_route_drop_no_conn_total 175767
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 414612
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1772
telemt_desync_full_logged_total 528
telemt_desync_suppressed_total 1244
telemt_desync_frames_bucket_total{bucket="1_2"} 419
telemt_desync_frames_bucket_total{bucket="3_10"} 674
telemt_desync_frames_bucket_total{bucket="gt_10"} 679
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 41015
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 37266
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3739
telemt_user_connections_total{user="hello"} 433457
telemt_user_connections_current{user="hello"} 167
telemt_user_octets_from_client{user="hello"} 9346456127 (8.70 GB)
telemt_user_octets_to_client{user="hello"} 177575224160 (165.38 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 54
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 120659.6 (33h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 196686
telemt_connections_bad_total 29165
telemt_handshake_timeouts_total 1731
telemt_upstream_connect_attempt_total 42629
telemt_upstream_connect_success_total 42227
telemt_upstream_connect_fail_total 402
telemt_upstream_connect_attempts_per_request{bucket="1"} 42629
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21169
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20917
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 141
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 402
telemt_me_keepalive_timeout_total 2500
telemt_me_reconnect_attempts_total 44769
telemt_me_reconnect_success_total 31339
telemt_me_reader_eof_total 33546
telemt_me_idle_close_by_peer_total 33546
telemt_me_route_drop_no_conn_total 58459
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 155544
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 645
telemt_desync_full_logged_total 155
telemt_desync_suppressed_total 490
telemt_desync_frames_bucket_total{bucket="1_2"} 103
telemt_desync_frames_bucket_total{bucket="3_10"} 317
telemt_desync_frames_bucket_total{bucket="gt_10"} 225
telemt_pool_swap_total 92
telemt_me_writer_removed_unexpected_total 32047
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 31321
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 708
telemt_user_connections_total{user="hello"} 160292
telemt_user_connections_current{user="hello"} 74
telemt_user_octets_from_client{user="hello"} 2380566657 (2.22 GB)
telemt_user_octets_to_client{user="hello"} 74093732111 (69.01 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 33
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 170444.1 (47h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 973600
telemt_connections_bad_total 36055
telemt_handshake_timeouts_total 26062
telemt_upstream_connect_attempt_total 35398
telemt_upstream_connect_success_total 35210
telemt_upstream_connect_fail_total 188
telemt_upstream_connect_attempts_per_request{bucket="1"} 35398
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16551
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18618
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 188
telemt_me_keepalive_timeout_total 4720
telemt_me_reconnect_attempts_total 31451
telemt_me_reconnect_success_total 26773
telemt_me_reader_eof_total 28743
telemt_me_idle_close_by_peer_total 28740
telemt_me_route_drop_no_conn_total 459340
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 903010
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 769
telemt_desync_full_logged_total 253
telemt_desync_suppressed_total 516
telemt_desync_frames_bucket_total{bucket="1_2"} 257
telemt_desync_frames_bucket_total{bucket="3_10"} 252
telemt_desync_frames_bucket_total{bucket="gt_10"} 260
telemt_pool_swap_total 162
telemt_me_writer_removed_unexpected_total 27258
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26766
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 485
telemt_user_connections_total{user="hello"} 875659
telemt_user_connections_current{user="hello"} 457
telemt_user_octets_from_client{user="hello"} 15049460456 (14.02 GB)
telemt_user_octets_to_client{user="hello"} 443086498304 (412.66 GB)
telemt_user_unique_ips_current{user="hello"} 163
telemt_user_unique_ips_recent_window{user="hello"} 64
```