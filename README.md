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

# Server Metrics 2026-03-18 17:10:42 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 6317.3 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194461
telemt_connections_bad_total 13451
telemt_handshake_timeouts_total 5562
telemt_upstream_connect_attempt_total 989
telemt_upstream_connect_success_total 989
telemt_upstream_connect_attempts_per_request{bucket="1"} 989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 466
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 25
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 659
telemt_me_reconnect_success_total 657
telemt_me_reader_eof_total 660
telemt_me_idle_close_by_peer_total 660
telemt_me_seq_mismatch_total 2
telemt_me_route_drop_no_conn_total 95556
telemt_me_route_drop_channel_closed_total 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 162199
telemt_me_writer_pick_total{mode="p2c",result="full"} 116
telemt_me_writer_pick_total{mode="p2c",result="closed"} 293
telemt_me_endpoint_quarantine_total 23
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 883
telemt_desync_full_logged_total 264
telemt_desync_suppressed_total 619
telemt_desync_frames_bucket_total{bucket="1_2"} 217
telemt_desync_frames_bucket_total{bucket="3_10"} 288
telemt_desync_frames_bucket_total{bucket="gt_10"} 378
telemt_pool_swap_total 4
telemt_me_writer_removed_unexpected_total 675
telemt_me_writer_restored_same_endpoint_total 644
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 75
telemt_me_writer_removed_unexpected_minus_restored_total 18
telemt_user_connections_total{user="hello"} 162122
telemt_user_connections_current{user="hello"} 1556
telemt_user_octets_from_client{user="hello"} 2214896532 (2.06 GB)
telemt_user_octets_to_client{user="hello"} 55238771652 (51.45 GB)
telemt_user_unique_ips_current{user="hello"} 491
telemt_user_unique_ips_recent_window{user="hello"} 204
```

## psb.hosting

```
telemt 3.3.22

telemt_uptime_seconds 11145.8 (3h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1117041
telemt_connections_bad_total 70998
telemt_connections_current 3952
telemt_connections_me_current 3952
telemt_handshake_timeouts_total 16588
telemt_upstream_connect_attempt_total 2017
telemt_upstream_connect_success_total 2007
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 2017
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 900
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 12
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 1416
telemt_me_reconnect_success_total 1406
telemt_me_reader_eof_total 1363
telemt_me_idle_close_by_peer_total 1362
telemt_me_route_drop_no_conn_total 1049842
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 975008
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 14
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2805
telemt_desync_full_logged_total 904
telemt_desync_suppressed_total 1901
telemt_desync_frames_bucket_total{bucket="1_2"} 555
telemt_desync_frames_bucket_total{bucket="3_10"} 1115
telemt_desync_frames_bucket_total{bucket="gt_10"} 1135
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1340
telemt_me_writer_restored_same_endpoint_total 1404
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 2874
telemt_user_connections_total{user="hello"} 974147
telemt_user_connections_current{user="hello"} 3952
telemt_user_octets_from_client{user="hello"} 12602617948 (11.74 GB)
telemt_user_octets_to_client{user="hello"} 289901047664 (269.99 GB)
telemt_user_unique_ips_current{user="hello"} 1195
telemt_user_unique_ips_recent_window{user="hello"} 519
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.22

telemt_uptime_seconds 11788.4 (3h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1130783
telemt_connections_bad_total 25589
telemt_connections_current 3019
telemt_connections_me_current 3019
telemt_handshake_timeouts_total 14312
telemt_upstream_connect_attempt_total 1857
telemt_upstream_connect_success_total 1845
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 1857
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 950
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 880
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 1213
telemt_me_reconnect_success_total 1202
telemt_me_reader_eof_total 1220
telemt_me_idle_close_by_peer_total 1219
telemt_me_route_drop_no_conn_total 1851836
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1013456
telemt_me_writer_pick_total{mode="p2c",result="full"} 30
telemt_me_writer_pick_total{mode="p2c",result="closed"} 61
telemt_me_endpoint_quarantine_total 12
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3775
telemt_desync_full_logged_total 963
telemt_desync_suppressed_total 2812
telemt_desync_frames_bucket_total{bucket="1_2"} 885
telemt_desync_frames_bucket_total{bucket="3_10"} 1717
telemt_desync_frames_bucket_total{bucket="gt_10"} 1173
telemt_pool_swap_total 9
telemt_me_writer_removed_unexpected_total 1196
telemt_me_writer_restored_same_endpoint_total 1191
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 1000
telemt_user_connections_total{user="hello"} 1013379
telemt_user_connections_current{user="hello"} 3019
telemt_user_octets_from_client{user="hello"} 8755423332 (8.15 GB)
telemt_user_octets_to_client{user="hello"} 178637583188 (166.37 GB)
telemt_user_unique_ips_current{user="hello"} 881
telemt_user_unique_ips_recent_window{user="hello"} 436
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 6303.2 (1h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 486104
telemt_connections_bad_total 88899
telemt_handshake_timeouts_total 4576
telemt_upstream_connect_attempt_total 1060
telemt_upstream_connect_success_total 1029
telemt_upstream_connect_fail_total 31
telemt_upstream_connect_attempts_per_request{bucket="1"} 1060
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 559
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 464
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31
telemt_me_keepalive_timeout_total 27
telemt_me_reconnect_attempts_total 1695
telemt_me_reconnect_success_total 695
telemt_me_reader_eof_total 723
telemt_me_idle_close_by_peer_total 723
telemt_me_route_drop_no_conn_total 204829
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 355760
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1305
telemt_desync_full_logged_total 451
telemt_desync_suppressed_total 854
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 421
telemt_desync_frames_bucket_total{bucket="gt_10"} 674
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 732
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 669
telemt_me_writer_restored_fallback_total 26
telemt_me_async_recovery_trigger_total 786
telemt_me_writer_removed_unexpected_minus_restored_total 37
telemt_user_connections_total{user="hello"} 355324
telemt_user_connections_current{user="hello"} 3341
telemt_user_octets_from_client{user="hello"} 5611574160 (5.23 GB)
telemt_user_octets_to_client{user="hello"} 145607768440 (135.61 GB)
telemt_user_unique_ips_current{user="hello"} 1055
telemt_user_unique_ips_recent_window{user="hello"} 456
```

## hostvds.com

```
telemt 3.3.22

telemt_uptime_seconds 11241.4 (3h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 205123
telemt_connections_bad_total 7681
telemt_connections_current 845
telemt_connections_me_current 845
telemt_relay_adaptive_promotions_total 18
telemt_relay_adaptive_hard_promotions_total 18
telemt_handshake_timeouts_total 1993
telemt_upstream_connect_attempt_total 6130
telemt_upstream_connect_success_total 6118
telemt_upstream_connect_fail_total 12
telemt_upstream_connect_attempts_per_request{bucket="1"} 6130
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3315
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2755
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 32
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 12
telemt_me_reconnect_attempts_total 331153
telemt_me_reconnect_success_total 1689
telemt_me_reader_eof_total 1658
telemt_me_idle_close_by_peer_total 1658
telemt_me_route_drop_no_conn_total 114999
telemt_me_route_drop_channel_closed_total 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 181707
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 9
telemt_me_endpoint_quarantine_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 368
telemt_desync_full_logged_total 133
telemt_desync_suppressed_total 235
telemt_desync_frames_bucket_total{bucket="1_2"} 63
telemt_desync_frames_bucket_total{bucket="3_10"} 150
telemt_desync_frames_bucket_total{bucket="gt_10"} 155
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1625
telemt_me_refill_failed_total 10448
telemt_me_writer_restored_same_endpoint_total 1678
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 40876
telemt_user_connections_total{user="hello"} 185429
telemt_user_connections_current{user="hello"} 845
telemt_user_octets_from_client{user="hello"} 2672491153 (2.49 GB)
telemt_user_octets_to_client{user="hello"} 39082563365 (36.40 GB)
telemt_user_msgs_from_client{user="hello"} 38712
telemt_user_msgs_to_client{user="hello"} 31668
telemt_user_unique_ips_current{user="hello"} 293
telemt_user_unique_ips_recent_window{user="hello"} 136
```

## 4vps.su

```
telemt 3.3.22

telemt_uptime_seconds 10307.8 (2h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 624931
telemt_connections_bad_total 32033
telemt_connections_current 2916
telemt_connections_me_current 2916
telemt_handshake_timeouts_total 12887
telemt_upstream_connect_attempt_total 1884
telemt_upstream_connect_success_total 1883
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 1884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1036
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 838
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 16835
telemt_me_reconnect_success_total 1323
telemt_me_reader_eof_total 1295
telemt_me_idle_close_by_peer_total 1295
telemt_me_route_drop_no_conn_total 377189
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="base"} 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 532996
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1988
telemt_desync_full_logged_total 691
telemt_desync_suppressed_total 1297
telemt_desync_frames_bucket_total{bucket="1_2"} 485
telemt_desync_frames_bucket_total{bucket="3_10"} 716
telemt_desync_frames_bucket_total{bucket="gt_10"} 787
telemt_pool_swap_total 8
telemt_me_writer_removed_unexpected_total 1282
telemt_me_refill_failed_total 741
telemt_me_writer_restored_same_endpoint_total 1262
telemt_me_writer_restored_fallback_total 61
telemt_me_async_recovery_trigger_total 9552
telemt_user_connections_total{user="hello"} 532043
telemt_user_connections_current{user="hello"} 2916
telemt_user_octets_from_client{user="hello"} 9364040116 (8.72 GB)
telemt_user_octets_to_client{user="hello"} 252478247508 (235.14 GB)
telemt_user_unique_ips_current{user="hello"} 878
telemt_user_unique_ips_recent_window{user="hello"} 381
```