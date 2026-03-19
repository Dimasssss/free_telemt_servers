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

# Server Metrics 2026-03-19 09:38:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 42576.2 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 889107
telemt_connections_bad_total 81403
telemt_connections_current 1559
telemt_connections_me_current 1559
telemt_handshake_timeouts_total 34055
telemt_upstream_connect_attempt_total 8110
telemt_upstream_connect_success_total 7969
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 8110
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3863
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4103
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 89
telemt_me_reconnect_attempts_total 6978
telemt_me_reconnect_success_total 5820
telemt_me_reader_eof_total 6170
telemt_me_idle_close_by_peer_total 6169
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 301007
telemt_me_route_drop_channel_closed_total 119
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 690969
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4240
telemt_desync_full_logged_total 1282
telemt_desync_suppressed_total 2958
telemt_desync_frames_bucket_total{bucket="1_2"} 1419
telemt_desync_frames_bucket_total{bucket="3_10"} 1552
telemt_desync_frames_bucket_total{bucket="gt_10"} 1269
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 5928
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5801
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 108
telemt_user_connections_total{user="hello"} 685392
telemt_user_connections_current{user="hello"} 1559
telemt_user_octets_from_client{user="hello"} 10946038492 (10.19 GB)
telemt_user_octets_to_client{user="hello"} 221473674072 (206.26 GB)
telemt_user_unique_ips_current{user="hello"} 552
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 42580.2 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2210979
telemt_connections_bad_total 135542
telemt_connections_current 4066
telemt_connections_me_current 4066
telemt_handshake_timeouts_total 48797
telemt_upstream_connect_attempt_total 8141
telemt_upstream_connect_success_total 7990
telemt_upstream_connect_fail_total 151
telemt_upstream_connect_attempts_per_request{bucket="1"} 8141
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3989
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3977
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 151
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 8170
telemt_me_reconnect_success_total 5822
telemt_me_reader_eof_total 6192
telemt_me_idle_close_by_peer_total 6192
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 970629
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1826527
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8336
telemt_desync_full_logged_total 2777
telemt_desync_suppressed_total 5559
telemt_desync_frames_bucket_total{bucket="1_2"} 1536
telemt_desync_frames_bucket_total{bucket="3_10"} 3240
telemt_desync_frames_bucket_total{bucket="gt_10"} 3560
telemt_pool_swap_total 32
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5996
telemt_me_refill_failed_total 73
telemt_me_writer_restored_same_endpoint_total 5800
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 174
telemt_user_connections_total{user="hello"} 1826287
telemt_user_connections_current{user="hello"} 4066
telemt_user_octets_from_client{user="hello"} 29511400036 (27.48 GB)
telemt_user_octets_to_client{user="hello"} 673398088640 (627.15 GB)
telemt_user_unique_ips_current{user="hello"} 1411
telemt_user_unique_ips_recent_window{user="hello"} 620
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 42577.9 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1857513
telemt_connections_bad_total 223274
telemt_connections_current 3024
telemt_connections_me_current 3024
telemt_handshake_timeouts_total 45277
telemt_upstream_connect_attempt_total 7632
telemt_upstream_connect_success_total 7632
telemt_upstream_connect_attempts_per_request{bucket="1"} 7632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4007
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3612
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 5499
telemt_me_reconnect_success_total 5464
telemt_me_reader_eof_total 5779
telemt_me_idle_close_by_peer_total 5779
telemt_me_route_drop_no_conn_total 867048
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1445459
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6566
telemt_desync_full_logged_total 2060
telemt_desync_suppressed_total 4506
telemt_desync_frames_bucket_total{bucket="1_2"} 1478
telemt_desync_frames_bucket_total{bucket="3_10"} 2403
telemt_desync_frames_bucket_total{bucket="gt_10"} 2685
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 5559
telemt_me_writer_restored_same_endpoint_total 5448
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 1444093
telemt_user_connections_current{user="hello"} 3024
telemt_user_octets_from_client{user="hello"} 22290714592 (20.76 GB)
telemt_user_octets_to_client{user="hello"} 665932134036 (620.20 GB)
telemt_user_unique_ips_current{user="hello"} 1062
telemt_user_unique_ips_recent_window{user="hello"} 472
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 42630.9 (11h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1926353
telemt_connections_bad_total 102610
telemt_connections_current 3080
telemt_connections_me_current 3080
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 48891
telemt_upstream_connect_attempt_total 15821
telemt_upstream_connect_success_total 15705
telemt_upstream_connect_fail_total 116
telemt_upstream_connect_attempts_per_request{bucket="1"} 15821
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11185
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4371
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 116
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 7797
telemt_me_reconnect_success_total 5382
telemt_me_reader_eof_total 5722
telemt_me_idle_close_by_peer_total 5721
telemt_me_route_drop_no_conn_total 968233
telemt_me_route_drop_channel_closed_total 15
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1441146
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5236
telemt_desync_full_logged_total 1778
telemt_desync_suppressed_total 3458
telemt_desync_frames_bucket_total{bucket="1_2"} 1076
telemt_desync_frames_bucket_total{bucket="3_10"} 2047
telemt_desync_frames_bucket_total{bucket="gt_10"} 2113
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5655
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5358
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 273
telemt_user_connections_total{user="hello"} 1447831
telemt_user_connections_current{user="hello"} 3080
telemt_user_octets_from_client{user="hello"} 17092016636 (15.92 GB)
telemt_user_octets_to_client{user="hello"} 420723488990 (391.83 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1027
telemt_user_unique_ips_recent_window{user="hello"} 483
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 42573.9 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2236517
telemt_connections_bad_total 537574
telemt_connections_current 3501
telemt_connections_me_current 3501
telemt_handshake_timeouts_total 47912
telemt_upstream_connect_attempt_total 7384
telemt_upstream_connect_success_total 7332
telemt_upstream_connect_fail_total 52
telemt_upstream_connect_attempts_per_request{bucket="1"} 7384
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3568
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 24
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 52
telemt_me_keepalive_timeout_total 15
telemt_me_reconnect_attempts_total 5221
telemt_me_reconnect_success_total 5177
telemt_me_reader_eof_total 5487
telemt_me_idle_close_by_peer_total 5487
telemt_me_route_drop_no_conn_total 641512
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1431242
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6611
telemt_desync_full_logged_total 2061
telemt_desync_suppressed_total 4550
telemt_desync_frames_bucket_total{bucket="1_2"} 1322
telemt_desync_frames_bucket_total{bucket="3_10"} 2908
telemt_desync_frames_bucket_total{bucket="gt_10"} 2381
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 5254
telemt_me_writer_restored_same_endpoint_total 5153
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 1430427
telemt_user_connections_current{user="hello"} 3501
telemt_user_octets_from_client{user="hello"} 26693873148 (24.86 GB)
telemt_user_octets_to_client{user="hello"} 632245863876 (588.82 GB)
telemt_user_unique_ips_current{user="hello"} 1190
telemt_user_unique_ips_recent_window{user="hello"} 546
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 42586.0 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 397642
telemt_connections_bad_total 17774
telemt_connections_current 957
telemt_connections_me_current 957
telemt_handshake_timeouts_total 3229
telemt_upstream_connect_attempt_total 10844
telemt_upstream_connect_success_total 10572
telemt_upstream_connect_fail_total 272
telemt_upstream_connect_attempts_per_request{bucket="1"} 10844
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5266
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5305
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 272
telemt_me_keepalive_timeout_total 10
telemt_me_reconnect_attempts_total 13799
telemt_me_reconnect_success_total 8413
telemt_me_reader_eof_total 8932
telemt_me_idle_close_by_peer_total 8932
telemt_me_route_drop_no_conn_total 203247
telemt_me_route_drop_channel_closed_total 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 356561
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 563
telemt_desync_full_logged_total 198
telemt_desync_suppressed_total 365
telemt_desync_frames_bucket_total{bucket="1_2"} 151
telemt_desync_frames_bucket_total{bucket="3_10"} 224
telemt_desync_frames_bucket_total{bucket="gt_10"} 188
telemt_pool_swap_total 21
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 8649
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 8383
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 236
telemt_user_connections_total{user="hello"} 356524
telemt_user_connections_current{user="hello"} 957
telemt_user_octets_from_client{user="hello"} 5289673696 (4.93 GB)
telemt_user_octets_to_client{user="hello"} 142246943796 (132.48 GB)
telemt_user_unique_ips_current{user="hello"} 338
telemt_user_unique_ips_recent_window{user="hello"} 127
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 42576.5 (11h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1513539
telemt_connections_bad_total 130998
telemt_connections_current 3272
telemt_connections_me_current 3272
telemt_handshake_timeouts_total 65561
telemt_upstream_connect_attempt_total 8660
telemt_upstream_connect_success_total 8659
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8660
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4646
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4010
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 50
telemt_me_reconnect_attempts_total 7842
telemt_me_reconnect_success_total 6491
telemt_me_reader_eof_total 6876
telemt_me_idle_close_by_peer_total 6875
telemt_me_route_drop_no_conn_total 592018
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1260570
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7132
telemt_desync_full_logged_total 2339
telemt_desync_suppressed_total 4793
telemt_desync_frames_bucket_total{bucket="1_2"} 1359
telemt_desync_frames_bucket_total{bucket="3_10"} 2681
telemt_desync_frames_bucket_total{bucket="gt_10"} 3092
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 6610
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6476
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 119
telemt_user_connections_total{user="hello"} 1259449
telemt_user_connections_current{user="hello"} 3272
telemt_user_octets_from_client{user="hello"} 17288572260 (16.10 GB)
telemt_user_octets_to_client{user="hello"} 613824977740 (571.67 GB)
telemt_user_unique_ips_current{user="hello"} 1019
telemt_user_unique_ips_recent_window{user="hello"} 441
```