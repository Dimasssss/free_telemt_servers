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

# Server Metrics 2026-03-17 15:45:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 75635.0 (21h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 840817
telemt_connections_bad_total 6309
telemt_handshake_timeouts_total 24322
telemt_upstream_connect_attempt_total 17975
telemt_upstream_connect_success_total 17504
telemt_upstream_connect_fail_total 471
telemt_upstream_connect_attempts_per_request{bucket="1"} 17975
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9187
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8158
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 159
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 471
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 169
telemt_me_reconnect_attempts_total 26130
telemt_me_reconnect_success_total 11420
telemt_me_reader_eof_total 12429
telemt_me_idle_close_by_peer_total 12428
telemt_me_route_drop_no_conn_total 352250
telemt_me_route_drop_channel_closed_total 85
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 764483
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5281
telemt_desync_full_logged_total 1470
telemt_desync_suppressed_total 3811
telemt_desync_frames_bucket_total{bucket="1_2"} 1513
telemt_desync_frames_bucket_total{bucket="3_10"} 2078
telemt_desync_frames_bucket_total{bucket="gt_10"} 1690
telemt_pool_swap_total 58
telemt_me_writer_removed_unexpected_total 12033
telemt_me_refill_failed_total 454
telemt_me_writer_restored_same_endpoint_total 11398
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 613
telemt_user_connections_total{user="hello"} 766305
telemt_user_connections_current{user="hello"} 953
telemt_user_octets_from_client{user="hello"} 12221916551 (11.38 GB)
telemt_user_octets_to_client{user="hello"} 252367157171 (235.04 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 152
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 75886.6 (21h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 558381
telemt_connections_bad_total 31861
telemt_handshake_timeouts_total 28438
telemt_upstream_connect_attempt_total 117878
telemt_upstream_connect_success_total 117320
telemt_upstream_connect_fail_total 553
telemt_upstream_connect_attempts_per_request{bucket="1"} 117873
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 94997
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13697
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8624
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 553
telemt_me_keepalive_timeout_total 330
telemt_me_reconnect_attempts_total 41500
telemt_me_reconnect_success_total 13489
telemt_me_reader_eof_total 14919
telemt_me_idle_close_by_peer_total 14919
telemt_me_route_drop_no_conn_total 194762
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 372799
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 9
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1485
telemt_desync_full_logged_total 467
telemt_desync_suppressed_total 1018
telemt_desync_frames_bucket_total{bucket="1_2"} 336
telemt_desync_frames_bucket_total{bucket="3_10"} 650
telemt_desync_frames_bucket_total{bucket="gt_10"} 499
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 14527
telemt_me_refill_failed_total 871
telemt_me_writer_restored_same_endpoint_total 13473
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 1038
telemt_user_connections_total{user="hello"} 472709
telemt_user_connections_current{user="hello"} 838
telemt_user_octets_from_client{user="hello"} 5239817404 (4.88 GB)
telemt_user_octets_to_client{user="hello"} 134111382632 (124.90 GB)
telemt_user_msgs_from_client{user="hello"} 1456830
telemt_user_msgs_to_client{user="hello"} 5295891
telemt_user_unique_ips_current{user="hello"} 203
telemt_user_unique_ips_recent_window{user="hello"} 108
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 75662.5 (21h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 282878
telemt_connections_bad_total 7843
telemt_handshake_timeouts_total 18655
telemt_upstream_connect_attempt_total 19647
telemt_upstream_connect_success_total 19544
telemt_upstream_connect_fail_total 103
telemt_upstream_connect_attempts_per_request{bucket="1"} 19647
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10656
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 75
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 103
telemt_me_keepalive_timeout_total 41
telemt_me_reconnect_attempts_total 30835
telemt_me_reconnect_success_total 15701
telemt_me_reader_eof_total 17038
telemt_me_idle_close_by_peer_total 17035
telemt_me_route_drop_no_conn_total 133181
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 242012
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 811
telemt_desync_full_logged_total 235
telemt_desync_suppressed_total 576
telemt_desync_frames_bucket_total{bucket="1_2"} 294
telemt_desync_frames_bucket_total{bucket="3_10"} 365
telemt_desync_frames_bucket_total{bucket="gt_10"} 152
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 16383
telemt_me_refill_failed_total 470
telemt_me_writer_restored_same_endpoint_total 15690
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 682
telemt_user_connections_total{user="hello"} 241863
telemt_user_connections_current{user="hello"} 330
telemt_user_octets_from_client{user="hello"} 18923590380 (17.62 GB)
telemt_user_octets_to_client{user="hello"} 58809302396 (54.77 GB)
telemt_user_unique_ips_current{user="hello"} 119
telemt_user_unique_ips_recent_window{user="hello"} 50
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 75721.8 (21h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 664995
telemt_connections_bad_total 8779
telemt_handshake_timeouts_total 14051
telemt_upstream_connect_attempt_total 46461
telemt_upstream_connect_success_total 46181
telemt_upstream_connect_fail_total 280
telemt_upstream_connect_attempts_per_request{bucket="1"} 46461
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9212
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 15
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 192
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 280
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 29660
telemt_me_reconnect_success_total 11965
telemt_me_reader_eof_total 13167
telemt_me_idle_close_by_peer_total 13166
telemt_me_route_drop_no_conn_total 255620
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 544602
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1867
telemt_desync_full_logged_total 633
telemt_desync_suppressed_total 1234
telemt_desync_frames_bucket_total{bucket="1_2"} 472
telemt_desync_frames_bucket_total{bucket="3_10"} 838
telemt_desync_frames_bucket_total{bucket="gt_10"} 557
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 12726
telemt_me_refill_failed_total 548
telemt_me_writer_restored_same_endpoint_total 11956
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 761
telemt_user_connections_total{user="hello"} 574767
telemt_user_connections_current{user="hello"} 731
telemt_user_octets_from_client{user="hello"} 6877585972 (6.41 GB)
telemt_user_octets_to_client{user="hello"} 173300361847 (161.40 GB)
telemt_user_msgs_from_client{user="hello"} 290835
telemt_user_msgs_to_client{user="hello"} 1735773
telemt_user_unique_ips_current{user="hello"} 154
telemt_user_unique_ips_recent_window{user="hello"} 92
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 75693.7 (21h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 301839
telemt_connections_bad_total 57757
telemt_handshake_timeouts_total 3726
telemt_upstream_connect_attempt_total 21618
telemt_upstream_connect_success_total 21143
telemt_upstream_connect_fail_total 475
telemt_upstream_connect_attempts_per_request{bucket="1"} 21618
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 9492
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 293
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 475
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 44150
telemt_me_reconnect_success_total 16926
telemt_me_reader_eof_total 18366
telemt_me_idle_close_by_peer_total 18364
telemt_me_route_drop_no_conn_total 86024
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 227667
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 10
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1129
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 887
telemt_desync_frames_bucket_total{bucket="1_2"} 563
telemt_desync_frames_bucket_total{bucket="3_10"} 436
telemt_desync_frames_bucket_total{bucket="gt_10"} 130
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 18056
telemt_me_refill_failed_total 846
telemt_me_writer_restored_same_endpoint_total 16918
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 1383
telemt_me_writer_removed_unexpected_minus_restored_total 1130
telemt_user_connections_total{user="hello"} 228189
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 2814925711 (2.62 GB)
telemt_user_octets_to_client{user="hello"} 84268884663 (78.48 GB)
telemt_user_msgs_from_client{user="hello"} 1159
telemt_user_msgs_to_client{user="hello"} 2341
telemt_user_unique_ips_current{user="hello"} 88
telemt_user_unique_ips_recent_window{user="hello"} 42
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 75855.2 (21h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 737022
telemt_connections_bad_total 59834
telemt_handshake_timeouts_total 7096
telemt_upstream_connect_attempt_total 15328
telemt_upstream_connect_success_total 15246
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15328
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7431
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7790
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 47
telemt_me_reconnect_attempts_total 21716
telemt_me_reconnect_success_total 11416
telemt_me_reader_eof_total 12419
telemt_me_idle_close_by_peer_total 12419
telemt_me_route_drop_no_conn_total 540874
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 750185
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1099
telemt_desync_full_logged_total 391
telemt_desync_suppressed_total 708
telemt_desync_frames_bucket_total{bucket="1_2"} 259
telemt_desync_frames_bucket_total{bucket="3_10"} 442
telemt_desync_frames_bucket_total{bucket="gt_10"} 398
telemt_pool_swap_total 63
telemt_me_writer_removed_unexpected_total 11917
telemt_me_refill_failed_total 319
telemt_me_writer_restored_same_endpoint_total 11402
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 501
telemt_user_connections_total{user="hello"} 633087
telemt_user_connections_current{user="hello"} 932
telemt_user_octets_from_client{user="hello"} 9270177564 (8.63 GB)
telemt_user_octets_to_client{user="hello"} 282575605764 (263.17 GB)
telemt_user_unique_ips_current{user="hello"} 328
telemt_user_unique_ips_recent_window{user="hello"} 141
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 23621.9 (6h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18331
telemt_connections_bad_total 82
telemt_handshake_timeouts_total 314
telemt_upstream_connect_attempt_total 12685
telemt_upstream_connect_success_total 12576
telemt_upstream_connect_fail_total 109
telemt_upstream_connect_attempts_per_request{bucket="1"} 12685
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6821
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5710
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 45
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 109
telemt_me_keepalive_timeout_total 51
telemt_me_reconnect_attempts_total 22757
telemt_me_reconnect_success_total 11188
telemt_me_reader_eof_total 11836
telemt_me_idle_close_by_peer_total 11836
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 6922
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 17462
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 13
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 7
telemt_me_writer_removed_unexpected_total 11673
telemt_me_refill_failed_total 359
telemt_me_writer_restored_same_endpoint_total 11172
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 485
telemt_user_connections_total{user="hello"} 17559
telemt_user_connections_current{user="hello"} 78
telemt_user_octets_from_client{user="hello"} 550578561 (525.07 MB)
telemt_user_octets_to_client{user="hello"} 24104641606 (22.45 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 25
telemt_user_unique_ips_recent_window{user="hello"} 13
```