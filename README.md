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

# Server Metrics 2026-03-19 06:18:40 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 30613.0 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 476952
telemt_connections_bad_total 48318
telemt_connections_current 1328
telemt_connections_me_current 1328
telemt_handshake_timeouts_total 21982
telemt_upstream_connect_attempt_total 5920
telemt_upstream_connect_success_total 5816
telemt_upstream_connect_fail_total 104
telemt_upstream_connect_attempts_per_request{bucket="1"} 5920
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2838
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2975
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 104
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 5445
telemt_me_reconnect_success_total 4303
telemt_me_reader_eof_total 4559
telemt_me_idle_close_by_peer_total 4558
telemt_me_seq_mismatch_total 7
telemt_me_route_drop_no_conn_total 126835
telemt_me_route_drop_channel_closed_total 33
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355918
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 27
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2239
telemt_desync_full_logged_total 645
telemt_desync_suppressed_total 1594
telemt_desync_frames_bucket_total{bucket="1_2"} 768
telemt_desync_frames_bucket_total{bucket="3_10"} 881
telemt_desync_frames_bucket_total{bucket="gt_10"} 590
telemt_pool_swap_total 28
telemt_me_writer_removed_unexpected_total 4379
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 4286
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 353165
telemt_user_connections_current{user="hello"} 1328
telemt_user_octets_from_client{user="hello"} 4490068912 (4.18 GB)
telemt_user_octets_to_client{user="hello"} 120462146796 (112.19 GB)
telemt_user_unique_ips_current{user="hello"} 478
telemt_user_unique_ips_recent_window{user="hello"} 198
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 30618.0 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1003263
telemt_connections_bad_total 58193
telemt_connections_current 3520
telemt_connections_me_current 3520
telemt_handshake_timeouts_total 27879
telemt_upstream_connect_attempt_total 5748
telemt_upstream_connect_success_total 5641
telemt_upstream_connect_fail_total 107
telemt_upstream_connect_attempts_per_request{bucket="1"} 5748
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2790
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 107
telemt_me_reconnect_attempts_total 5258
telemt_me_reconnect_success_total 4113
telemt_me_reader_eof_total 4363
telemt_me_idle_close_by_peer_total 4363
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 320754
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 827447
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3486
telemt_desync_full_logged_total 1192
telemt_desync_suppressed_total 2294
telemt_desync_frames_bucket_total{bucket="1_2"} 631
telemt_desync_frames_bucket_total{bucket="3_10"} 1319
telemt_desync_frames_bucket_total{bucket="gt_10"} 1536
telemt_pool_swap_total 26
telemt_me_writer_removed_unexpected_total 4225
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 4093
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 827395
telemt_user_connections_current{user="hello"} 3520
telemt_user_octets_from_client{user="hello"} 18360567644 (17.10 GB)
telemt_user_octets_to_client{user="hello"} 367800212192 (342.54 GB)
telemt_user_unique_ips_current{user="hello"} 1260
telemt_user_unique_ips_recent_window{user="hello"} 514
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 30615.0 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 860083
telemt_connections_bad_total 140804
telemt_connections_current 3007
telemt_connections_me_current 3007
telemt_handshake_timeouts_total 27090
telemt_upstream_connect_attempt_total 5600
telemt_upstream_connect_success_total 5600
telemt_upstream_connect_attempts_per_request{bucket="1"} 5600
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2864
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2729
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 4095
telemt_me_reconnect_success_total 4076
telemt_me_reader_eof_total 4305
telemt_me_idle_close_by_peer_total 4305
telemt_me_route_drop_no_conn_total 268325
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 627585
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3203
telemt_desync_full_logged_total 1027
telemt_desync_suppressed_total 2176
telemt_desync_frames_bucket_total{bucket="1_2"} 578
telemt_desync_frames_bucket_total{bucket="3_10"} 1141
telemt_desync_frames_bucket_total{bucket="gt_10"} 1484
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 4150
telemt_me_writer_restored_same_endpoint_total 4060
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 74
telemt_user_connections_total{user="hello"} 627344
telemt_user_connections_current{user="hello"} 3007
telemt_user_octets_from_client{user="hello"} 11905542664 (11.09 GB)
telemt_user_octets_to_client{user="hello"} 360843200492 (336.06 GB)
telemt_user_unique_ips_current{user="hello"} 986
telemt_user_unique_ips_recent_window{user="hello"} 401
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 30668.2 (8h 31m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 928837
telemt_connections_bad_total 88159
telemt_connections_current 2679
telemt_connections_me_current 2679
telemt_handshake_timeouts_total 22522
telemt_upstream_connect_attempt_total 5422
telemt_upstream_connect_success_total 5422
telemt_upstream_connect_attempts_per_request{bucket="1"} 5422
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2745
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2662
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_reconnect_attempts_total 4920
telemt_me_reconnect_success_total 3870
telemt_me_reader_eof_total 4108
telemt_me_idle_close_by_peer_total 4107
telemt_me_route_drop_no_conn_total 286165
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 618635
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2385
telemt_desync_full_logged_total 852
telemt_desync_suppressed_total 1533
telemt_desync_frames_bucket_total{bucket="1_2"} 426
telemt_desync_frames_bucket_total{bucket="3_10"} 952
telemt_desync_frames_bucket_total{bucket="gt_10"} 1007
telemt_pool_swap_total 30
telemt_me_writer_removed_unexpected_total 3959
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 3846
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 617544
telemt_user_connections_current{user="hello"} 2679
telemt_user_octets_from_client{user="hello"} 9713828556 (9.05 GB)
telemt_user_octets_to_client{user="hello"} 236778410624 (220.52 GB)
telemt_user_unique_ips_current{user="hello"} 888
telemt_user_unique_ips_recent_window{user="hello"} 404
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 30611.7 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1120883
telemt_connections_bad_total 313314
telemt_connections_current 2777
telemt_connections_me_current 2777
telemt_handshake_timeouts_total 28495
telemt_upstream_connect_attempt_total 5445
telemt_upstream_connect_success_total 5411
telemt_upstream_connect_fail_total 34
telemt_upstream_connect_attempts_per_request{bucket="1"} 5445
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2730
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2662
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 34
telemt_me_reconnect_attempts_total 3915
telemt_me_reconnect_success_total 3889
telemt_me_reader_eof_total 4110
telemt_me_idle_close_by_peer_total 4110
telemt_me_route_drop_no_conn_total 273540
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 663104
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3303
telemt_desync_full_logged_total 1089
telemt_desync_suppressed_total 2214
telemt_desync_frames_bucket_total{bucket="1_2"} 752
telemt_desync_frames_bucket_total{bucket="3_10"} 1444
telemt_desync_frames_bucket_total{bucket="gt_10"} 1107
telemt_pool_swap_total 31
telemt_me_writer_removed_unexpected_total 3932
telemt_me_writer_restored_same_endpoint_total 3865
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 663020
telemt_user_connections_current{user="hello"} 2777
telemt_user_octets_from_client{user="hello"} 16503938156 (15.37 GB)
telemt_user_octets_to_client{user="hello"} 354092536256 (329.77 GB)
telemt_user_unique_ips_current{user="hello"} 994
telemt_user_unique_ips_recent_window{user="hello"} 437
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 30623.5 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 188969
telemt_connections_bad_total 12134
telemt_connections_current 627
telemt_connections_me_current 627
telemt_handshake_timeouts_total 1517
telemt_upstream_connect_attempt_total 8254
telemt_upstream_connect_success_total 8043
telemt_upstream_connect_fail_total 211
telemt_upstream_connect_attempts_per_request{bucket="1"} 8254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3928
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 211
telemt_me_reconnect_attempts_total 10963
telemt_me_reconnect_success_total 6525
telemt_me_reader_eof_total 6903
telemt_me_idle_close_by_peer_total 6903
telemt_me_route_drop_no_conn_total 76021
telemt_me_route_drop_channel_closed_total 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 164553
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 224
telemt_desync_full_logged_total 80
telemt_desync_suppressed_total 144
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 94
telemt_desync_frames_bucket_total{bucket="gt_10"} 67
telemt_pool_swap_total 15
telemt_me_writer_removed_unexpected_total 6688
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6495
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 164547
telemt_user_connections_current{user="hello"} 627
telemt_user_octets_from_client{user="hello"} 2715524352 (2.53 GB)
telemt_user_octets_to_client{user="hello"} 90130460620 (83.94 GB)
telemt_user_unique_ips_current{user="hello"} 268
telemt_user_unique_ips_recent_window{user="hello"} 102
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 30614.1 (8h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 686421
telemt_connections_bad_total 83570
telemt_connections_current 2917
telemt_connections_me_current 2917
telemt_handshake_timeouts_total 29783
telemt_upstream_connect_attempt_total 6120
telemt_upstream_connect_success_total 6120
telemt_upstream_connect_attempts_per_request{bucket="1"} 6120
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3250
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_me_reconnect_attempts_total 4621
telemt_me_reconnect_success_total 4607
telemt_me_reader_eof_total 4872
telemt_me_idle_close_by_peer_total 4872
telemt_me_route_drop_no_conn_total 241793
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 549765
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3107
telemt_desync_full_logged_total 1106
telemt_desync_suppressed_total 2001
telemt_desync_frames_bucket_total{bucket="1_2"} 613
telemt_desync_frames_bucket_total{bucket="3_10"} 1190
telemt_desync_frames_bucket_total{bucket="gt_10"} 1304
telemt_pool_swap_total 32
telemt_me_writer_removed_unexpected_total 4660
telemt_me_writer_restored_same_endpoint_total 4592
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 549572
telemt_user_connections_current{user="hello"} 2917
telemt_user_octets_from_client{user="hello"} 7210850560 (6.72 GB)
telemt_user_octets_to_client{user="hello"} 313597414048 (292.06 GB)
telemt_user_unique_ips_current{user="hello"} 914
telemt_user_unique_ips_recent_window{user="hello"} 372
```