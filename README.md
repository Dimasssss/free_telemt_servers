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

## 4vps.su
- Локация: Польша, Варшава
- Тариф: PL-cx21
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 2 Gbit/s
- Цена в месяц: 770 RUB
- Оплачен до: 16 апреля
- Ссылка:
```bash
tg://proxy?server=s7.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

# Server Metrics 2026-03-17 14:59:50 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 72874.1 (20h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 788233
telemt_connections_bad_total 5925
telemt_handshake_timeouts_total 23289
telemt_upstream_connect_attempt_total 17489
telemt_upstream_connect_success_total 17029
telemt_upstream_connect_fail_total 460
telemt_upstream_connect_attempts_per_request{bucket="1"} 17489
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7941
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 460
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 121
telemt_me_reconnect_attempts_total 24420
telemt_me_reconnect_success_total 11094
telemt_me_reader_eof_total 12061
telemt_me_idle_close_by_peer_total 12060
telemt_me_route_drop_no_conn_total 317638
telemt_me_route_drop_channel_closed_total 79
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 715206
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5040
telemt_desync_full_logged_total 1393
telemt_desync_suppressed_total 3647
telemt_desync_frames_bucket_total{bucket="1_2"} 1470
telemt_desync_frames_bucket_total{bucket="3_10"} 2003
telemt_desync_frames_bucket_total{bucket="gt_10"} 1567
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 11663
telemt_me_refill_failed_total 411
telemt_me_writer_restored_same_endpoint_total 11072
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 569
telemt_user_connections_total{user="hello"} 717057
telemt_user_connections_current{user="hello"} 1027
telemt_user_octets_from_client{user="hello"} 11786363291 (10.98 GB)
telemt_user_octets_to_client{user="hello"} 239041242863 (222.62 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 331
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 73126.5 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 507109
telemt_connections_bad_total 31699
telemt_handshake_timeouts_total 25623
telemt_upstream_connect_attempt_total 76830
telemt_upstream_connect_success_total 76326
telemt_upstream_connect_fail_total 504
telemt_upstream_connect_attempts_per_request{bucket="1"} 76830
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 58923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11915
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5486
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 504
telemt_me_keepalive_timeout_total 329
telemt_me_reconnect_attempts_total 36977
telemt_me_reconnect_success_total 13419
telemt_me_reader_eof_total 14712
telemt_me_idle_close_by_peer_total 14712
telemt_me_route_drop_no_conn_total 191762
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 366653
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 8
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1473
telemt_desync_full_logged_total 464
telemt_desync_suppressed_total 1009
telemt_desync_frames_bucket_total{bucket="1_2"} 332
telemt_desync_frames_bucket_total{bucket="3_10"} 645
telemt_desync_frames_bucket_total{bucket="gt_10"} 496
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14318
telemt_me_refill_failed_total 732
telemt_me_writer_restored_same_endpoint_total 13403
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 899
telemt_user_connections_total{user="hello"} 425777
telemt_user_connections_current{user="hello"} 604
telemt_user_octets_from_client{user="hello"} 4633678963 (4.32 GB)
telemt_user_octets_to_client{user="hello"} 126495185319 (117.81 GB)
telemt_user_msgs_from_client{user="hello"} 833098
telemt_user_msgs_to_client{user="hello"} 2823658
telemt_user_unique_ips_current{user="hello"} 176
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 72901.2 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 262481
telemt_connections_bad_total 7831
telemt_handshake_timeouts_total 17346
telemt_upstream_connect_attempt_total 19133
telemt_upstream_connect_success_total 19036
telemt_upstream_connect_fail_total 97
telemt_upstream_connect_attempts_per_request{bucket="1"} 19133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8545
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10411
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 97
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 26421
telemt_me_reconnect_success_total 15353
telemt_me_reader_eof_total 16565
telemt_me_idle_close_by_peer_total 16562
telemt_me_route_drop_no_conn_total 121419
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 223650
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 793
telemt_desync_full_logged_total 229
telemt_desync_suppressed_total 564
telemt_desync_frames_bucket_total{bucket="1_2"} 289
telemt_desync_frames_bucket_total{bucket="3_10"} 357
telemt_desync_frames_bucket_total{bucket="gt_10"} 147
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 15907
telemt_me_refill_failed_total 343
telemt_me_writer_restored_same_endpoint_total 15342
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 554
telemt_user_connections_total{user="hello"} 223513
telemt_user_connections_current{user="hello"} 363
telemt_user_octets_from_client{user="hello"} 18280250688 (17.02 GB)
telemt_user_octets_to_client{user="hello"} 55546388136 (51.73 GB)
telemt_user_unique_ips_current{user="hello"} 128
telemt_user_unique_ips_recent_window{user="hello"} 59
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 72960.4 (20h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 605002
telemt_connections_bad_total 8560
telemt_handshake_timeouts_total 13403
telemt_upstream_connect_attempt_total 16779
telemt_upstream_connect_success_total 16621
telemt_upstream_connect_fail_total 158
telemt_upstream_connect_attempts_per_request{bucket="1"} 16779
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8338
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8164
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 110
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 158
telemt_me_keepalive_timeout_total 17
telemt_me_reconnect_attempts_total 25348
telemt_me_reconnect_success_total 11909
telemt_me_reader_eof_total 12980
telemt_me_idle_close_by_peer_total 12979
telemt_me_route_drop_no_conn_total 227637
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 519702
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1817
telemt_desync_full_logged_total 613
telemt_desync_suppressed_total 1204
telemt_desync_frames_bucket_total{bucket="1_2"} 457
telemt_desync_frames_bucket_total{bucket="3_10"} 812
telemt_desync_frames_bucket_total{bucket="gt_10"} 548
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12536
telemt_me_refill_failed_total 415
telemt_me_writer_restored_same_endpoint_total 11900
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 627
telemt_user_connections_total{user="hello"} 520528
telemt_user_connections_current{user="hello"} 684
telemt_user_octets_from_client{user="hello"} 6437047822 (5.99 GB)
telemt_user_octets_to_client{user="hello"} 165441391347 (154.08 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 179
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 72932.4 (20h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 286582
telemt_connections_bad_total 57210
telemt_handshake_timeouts_total 3623
telemt_upstream_connect_attempt_total 21170
telemt_upstream_connect_success_total 20700
telemt_upstream_connect_fail_total 470
telemt_upstream_connect_attempts_per_request{bucket="1"} 21170
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9306
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11106
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 288
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 470
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 39807
telemt_me_reconnect_success_total 16648
telemt_me_reader_eof_total 17963
telemt_me_idle_close_by_peer_total 17961
telemt_me_route_drop_no_conn_total 80701
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 213654
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1120
telemt_desync_full_logged_total 238
telemt_desync_suppressed_total 882
telemt_desync_frames_bucket_total{bucket="1_2"} 560
telemt_desync_frames_bucket_total{bucket="3_10"} 431
telemt_desync_frames_bucket_total{bucket="gt_10"} 129
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 17651
telemt_me_refill_failed_total 719
telemt_me_writer_restored_same_endpoint_total 16640
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1003
telemt_user_connections_total{user="hello"} 214160
telemt_user_connections_current{user="hello"} 267
telemt_user_octets_from_client{user="hello"} 2676614455 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 76189765291 (70.96 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 73094.8 (20h 18m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 690727
telemt_connections_bad_total 55098
telemt_handshake_timeouts_total 6847
telemt_upstream_connect_attempt_total 14693
telemt_upstream_connect_success_total 14611
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 14693
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7390
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 39
telemt_me_reconnect_attempts_total 21211
telemt_me_reconnect_success_total 10920
telemt_me_reader_eof_total 11891
telemt_me_idle_close_by_peer_total 11891
telemt_me_route_drop_no_conn_total 496335
telemt_me_route_drop_channel_closed_total 38
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 698073
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 983
telemt_desync_full_logged_total 358
telemt_desync_suppressed_total 625
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 392
telemt_desync_frames_bucket_total{bucket="gt_10"} 342
telemt_pool_swap_total 61
telemt_me_writer_removed_unexpected_total 11412
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 10906
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 593476
telemt_user_connections_current{user="hello"} 976
telemt_user_octets_from_client{user="hello"} 8773692700 (8.17 GB)
telemt_user_octets_to_client{user="hello"} 265532721744 (247.30 GB)
telemt_user_unique_ips_current{user="hello"} 349
telemt_user_unique_ips_recent_window{user="hello"} 154
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 20860.6 (5h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16331
telemt_connections_bad_total 71
telemt_handshake_timeouts_total 309
telemt_upstream_connect_attempt_total 11321
telemt_upstream_connect_success_total 11225
telemt_upstream_connect_fail_total 96
telemt_upstream_connect_attempts_per_request{bucket="1"} 11321
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6120
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5082
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 96
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 21533
telemt_me_reconnect_success_total 9978
telemt_me_reader_eof_total 10576
telemt_me_idle_close_by_peer_total 10576
telemt_me_seq_mismatch_total 10
telemt_me_route_drop_no_conn_total 5979
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15540
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 6
telemt_me_writer_removed_unexpected_total 10442
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 9963
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 464
telemt_user_connections_total{user="hello"} 15638
telemt_user_connections_current{user="hello"} 50
telemt_user_octets_from_client{user="hello"} 478783481 (456.60 MB)
telemt_user_octets_to_client{user="hello"} 23241444826 (21.65 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 17
telemt_user_unique_ips_recent_window{user="hello"} 9
```