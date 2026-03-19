# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 19 апреля
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

# Server Metrics 2026-03-19 15:00:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 349.9 (0h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 16223
telemt_connections_current 137
telemt_connections_direct_current 137
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_demotions_total 17
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 11629
telemt_upstream_connect_attempt_total 1472
telemt_upstream_connect_success_total 1472
telemt_upstream_connect_attempts_per_request{bucket="1"} 1472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1370
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 101
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_user_connections_total{user="hello"} 1470
telemt_user_connections_current{user="hello"} 137
telemt_user_octets_from_client{user="hello"} 36468117 (34.78 MB)
telemt_user_octets_to_client{user="hello"} 634621194 (605.22 MB)
telemt_user_msgs_from_client{user="hello"} 15926
telemt_user_msgs_to_client{user="hello"} 33779
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 24
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 8245.1 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 883245
telemt_connections_bad_total 31587
telemt_connections_current 4377
telemt_connections_me_current 4377
telemt_handshake_timeouts_total 18725
telemt_upstream_connect_attempt_total 2884
telemt_upstream_connect_success_total 2860
telemt_upstream_connect_fail_total 24
telemt_upstream_connect_attempts_per_request{bucket="1"} 2884
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2105
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 732
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 23
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 24
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 5369
telemt_me_reconnect_success_total 1154
telemt_me_reader_eof_total 1260
telemt_me_idle_close_by_peer_total 1260
telemt_me_route_drop_no_conn_total 658875
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 751944
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2762
telemt_desync_full_logged_total 888
telemt_desync_suppressed_total 1874
telemt_desync_frames_bucket_total{bucket="1_2"} 497
telemt_desync_frames_bucket_total{bucket="3_10"} 1081
telemt_desync_frames_bucket_total{bucket="gt_10"} 1184
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 27
telemt_me_writer_removed_unexpected_total 1276
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 1099
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 122
telemt_user_connections_total{user="hello"} 752241
telemt_user_connections_current{user="hello"} 4377
telemt_user_octets_from_client{user="hello"} 9361558002 (8.72 GB)
telemt_user_octets_to_client{user="hello"} 203176870998 (189.22 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1454
telemt_user_unique_ips_recent_window{user="hello"} 842
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 8223.9 (2h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 857125
telemt_connections_bad_total 96072
telemt_connections_current 3273
telemt_connections_me_current 3273
telemt_handshake_timeouts_total 8389
telemt_upstream_connect_attempt_total 1406
telemt_upstream_connect_success_total 1393
telemt_upstream_connect_fail_total 13
telemt_upstream_connect_attempts_per_request{bucket="1"} 1406
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 783
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 604
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 6
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 1823
telemt_me_reconnect_success_total 918
telemt_me_reader_eof_total 876
telemt_me_idle_close_by_peer_total 875
telemt_me_route_drop_no_conn_total 787716
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 653293
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2307
telemt_desync_full_logged_total 603
telemt_desync_suppressed_total 1704
telemt_desync_frames_bucket_total{bucket="1_2"} 663
telemt_desync_frames_bucket_total{bucket="3_10"} 846
telemt_desync_frames_bucket_total{bucket="gt_10"} 798
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 31
telemt_me_writer_removed_unexpected_total 885
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 917
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_user_connections_total{user="hello"} 650532
telemt_user_connections_current{user="hello"} 3273
telemt_user_octets_from_client{user="hello"} 6796230336 (6.33 GB)
telemt_user_octets_to_client{user="hello"} 173640682016 (161.72 GB)
telemt_user_unique_ips_current{user="hello"} 1093
telemt_user_unique_ips_recent_window{user="hello"} 599
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 8211.2 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 686713
telemt_connections_bad_total 43705
telemt_connections_current 3155
telemt_connections_me_current 3155
telemt_handshake_timeouts_total 11001
telemt_upstream_connect_attempt_total 10453
telemt_upstream_connect_success_total 9952
telemt_upstream_connect_fail_total 501
telemt_upstream_connect_attempts_per_request{bucket="1"} 10453
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8050
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1727
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 19
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 156
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 501
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 1326
telemt_me_reconnect_success_total 1016
telemt_me_reader_eof_total 997
telemt_me_idle_close_by_peer_total 996
telemt_me_route_drop_no_conn_total 454714
telemt_me_route_drop_channel_closed_total 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 571330
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2563
telemt_desync_full_logged_total 858
telemt_desync_suppressed_total 1705
telemt_desync_frames_bucket_total{bucket="1_2"} 535
telemt_desync_frames_bucket_total{bucket="3_10"} 987
telemt_desync_frames_bucket_total{bucket="gt_10"} 1041
telemt_pool_swap_total 3
telemt_me_writer_close_signal_drop_total 77
telemt_me_writer_removed_unexpected_total 1136
telemt_me_refill_failed_total 3
telemt_me_writer_restored_same_endpoint_total 1012
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 120
telemt_user_connections_total{user="hello"} 579307
telemt_user_connections_current{user="hello"} 3155
telemt_user_octets_from_client{user="hello"} 11368037859 (10.59 GB)
telemt_user_octets_to_client{user="hello"} 132721027604 (123.61 GB)
telemt_user_msgs_from_client{user="hello"} 16739
telemt_user_msgs_to_client{user="hello"} 18599
telemt_user_unique_ips_current{user="hello"} 1057
telemt_user_unique_ips_recent_window{user="hello"} 606
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 61934.5 (17h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4344365
telemt_connections_bad_total 811894
telemt_connections_current 3929
telemt_connections_me_current 3929
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 83860
telemt_upstream_connect_attempt_total 62894
telemt_upstream_connect_success_total 60410
telemt_upstream_connect_fail_total 2484
telemt_upstream_connect_attempts_per_request{bucket="1"} 62894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51914
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7474
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1022
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2484
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 73527
telemt_me_reconnect_success_total 8129
telemt_me_reader_eof_total 8557
telemt_me_idle_close_by_peer_total 8554
telemt_me_route_drop_no_conn_total 2054047
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2981587
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12865
telemt_desync_full_logged_total 3972
telemt_desync_suppressed_total 8893
telemt_desync_frames_bucket_total{bucket="1_2"} 2186
telemt_desync_frames_bucket_total{bucket="3_10"} 5514
telemt_desync_frames_bucket_total{bucket="gt_10"} 5165
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 8344
telemt_me_refill_failed_total 2040
telemt_me_writer_restored_same_endpoint_total 8105
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 3030213
telemt_user_connections_current{user="hello"} 3929
telemt_user_octets_from_client{user="hello"} 48122817707 (44.82 GB)
telemt_user_octets_to_client{user="hello"} 1073332412964 (999.62 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1182
telemt_user_unique_ips_recent_window{user="hello"} 707
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 8177.7 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 185285
telemt_connections_bad_total 9714
telemt_connections_current 1093
telemt_connections_me_current 1093
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 6135
telemt_upstream_connect_attempt_total 4218
telemt_upstream_connect_success_total 4081
telemt_upstream_connect_fail_total 137
telemt_upstream_connect_attempts_per_request{bucket="1"} 4218
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1489
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2421
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 164
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 137
telemt_me_reconnect_attempts_total 1117
telemt_me_reconnect_success_total 1089
telemt_me_reader_eof_total 1071
telemt_me_idle_close_by_peer_total 1071
telemt_me_route_drop_no_conn_total 120478
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 157881
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 464
telemt_me_writer_pick_total{mode="p2c",result="full"} 2833
telemt_me_writer_pick_total{mode="p2c",result="closed"} 24
telemt_me_writer_pick_blocking_fallback_total 3285
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 454
telemt_desync_full_logged_total 140
telemt_desync_suppressed_total 314
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 188
telemt_desync_frames_bucket_total{bucket="gt_10"} 192
telemt_pool_swap_total 5
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 1060
telemt_me_writer_restored_same_endpoint_total 1080
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 179
telemt_me_async_recovery_trigger_total 1239
telemt_user_connections_total{user="hello"} 160504
telemt_user_connections_current{user="hello"} 1093
telemt_user_octets_from_client{user="hello"} 2277744656 (2.12 GB)
telemt_user_octets_to_client{user="hello"} 41059210770 (38.24 GB)
telemt_user_msgs_from_client{user="hello"} 7378
telemt_user_msgs_to_client{user="hello"} 12667
telemt_user_unique_ips_current{user="hello"} 378
telemt_user_unique_ips_recent_window{user="hello"} 179
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 8175.7 (2h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 559159
telemt_connections_bad_total 37704
telemt_connections_current 3410
telemt_connections_me_current 3410
telemt_handshake_timeouts_total 10179
telemt_upstream_connect_attempt_total 1290
telemt_upstream_connect_success_total 1280
telemt_upstream_connect_fail_total 10
telemt_upstream_connect_attempts_per_request{bucket="1"} 1290
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 706
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 570
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 845
telemt_me_reconnect_success_total 831
telemt_me_reader_eof_total 859
telemt_me_idle_close_by_peer_total 859
telemt_me_route_drop_no_conn_total 196360
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 481792
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2638
telemt_desync_full_logged_total 794
telemt_desync_suppressed_total 1844
telemt_desync_frames_bucket_total{bucket="1_2"} 518
telemt_desync_frames_bucket_total{bucket="3_10"} 868
telemt_desync_frames_bucket_total{bucket="gt_10"} 1252
telemt_pool_swap_total 6
telemt_me_writer_close_signal_drop_total 25
telemt_me_writer_removed_unexpected_total 858
telemt_me_writer_restored_same_endpoint_total 814
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 481427
telemt_user_connections_current{user="hello"} 3410
telemt_user_octets_from_client{user="hello"} 6734051220 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 203225425396 (189.27 GB)
telemt_user_unique_ips_current{user="hello"} 1086
telemt_user_unique_ips_recent_window{user="hello"} 615
```