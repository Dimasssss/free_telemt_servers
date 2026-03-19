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

# Server Metrics 2026-03-19 11:51:15 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 50567.0 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1228450
telemt_connections_bad_total 102787
telemt_connections_current 1643
telemt_connections_me_current 1643
telemt_handshake_timeouts_total 42767
telemt_upstream_connect_attempt_total 9683
telemt_upstream_connect_success_total 9516
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 9683
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4669
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4844
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 8842
telemt_me_reconnect_success_total 6955
telemt_me_reader_eof_total 7364
telemt_me_idle_close_by_peer_total 7361
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 510802
telemt_me_route_drop_channel_closed_total 202
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 963212
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5355
telemt_desync_full_logged_total 1638
telemt_desync_suppressed_total 3717
telemt_desync_frames_bucket_total{bucket="1_2"} 1729
telemt_desync_frames_bucket_total{bucket="3_10"} 1941
telemt_desync_frames_bucket_total{bucket="gt_10"} 1685
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 7114
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 6934
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 957135
telemt_user_connections_current{user="hello"} 1643
telemt_user_octets_from_client{user="hello"} 14740249352 (13.73 GB)
telemt_user_octets_to_client{user="hello"} 290634903132 (270.67 GB)
telemt_user_unique_ips_current{user="hello"} 571
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 50570.7 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3436820
telemt_connections_bad_total 226968
telemt_connections_current 3724
telemt_connections_me_current 3724
telemt_handshake_timeouts_total 61884
telemt_upstream_connect_attempt_total 9547
telemt_upstream_connect_success_total 9370
telemt_upstream_connect_fail_total 177
telemt_upstream_connect_attempts_per_request{bucket="1"} 9547
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4746
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4593
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 177
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 16053
telemt_me_reconnect_success_total 6779
telemt_me_reader_eof_total 7385
telemt_me_idle_close_by_peer_total 7384
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 2797108
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2887461
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11260
telemt_desync_full_logged_total 3769
telemt_desync_suppressed_total 7491
telemt_desync_frames_bucket_total{bucket="1_2"} 2190
telemt_desync_frames_bucket_total{bucket="3_10"} 4445
telemt_desync_frames_bucket_total{bucket="gt_10"} 4625
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7188
telemt_me_refill_failed_total 289
telemt_me_writer_restored_same_endpoint_total 6756
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 409
telemt_user_connections_total{user="hello"} 2887087
telemt_user_connections_current{user="hello"} 3724
telemt_user_octets_from_client{user="hello"} 37245707932 (34.69 GB)
telemt_user_octets_to_client{user="hello"} 842334766716 (784.49 GB)
telemt_user_unique_ips_current{user="hello"} 1324
telemt_user_unique_ips_recent_window{user="hello"} 667
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 50567.9 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2594271
telemt_connections_bad_total 301346
telemt_connections_current 3357
telemt_connections_me_current 3357
telemt_handshake_timeouts_total 52418
telemt_upstream_connect_attempt_total 9149
telemt_upstream_connect_success_total 9149
telemt_upstream_connect_attempts_per_request{bucket="1"} 9149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4381
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 7749
telemt_me_reconnect_success_total 6555
telemt_me_reader_eof_total 6952
telemt_me_idle_close_by_peer_total 6951
telemt_me_route_drop_no_conn_total 1586898
telemt_me_route_drop_channel_closed_total 85
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2044968
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8455
telemt_desync_full_logged_total 2681
telemt_desync_suppressed_total 5774
telemt_desync_frames_bucket_total{bucket="1_2"} 1915
telemt_desync_frames_bucket_total{bucket="3_10"} 3097
telemt_desync_frames_bucket_total{bucket="gt_10"} 3443
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6704
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6539
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 149
telemt_user_connections_total{user="hello"} 2042739
telemt_user_connections_current{user="hello"} 3357
telemt_user_octets_from_client{user="hello"} 28528688412 (26.57 GB)
telemt_user_octets_to_client{user="hello"} 870118726024 (810.36 GB)
telemt_user_unique_ips_current{user="hello"} 1132
telemt_user_unique_ips_recent_window{user="hello"} 559
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 50620.9 (14h 3m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2659777
telemt_connections_bad_total 139508
telemt_connections_current 2954
telemt_connections_me_current 2954
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 65209
telemt_upstream_connect_attempt_total 17473
telemt_upstream_connect_success_total 17294
telemt_upstream_connect_fail_total 179
telemt_upstream_connect_attempts_per_request{bucket="1"} 17473
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 12019
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5106
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 167
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 179
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 10891
telemt_me_reconnect_success_total 6540
telemt_me_reader_eof_total 6962
telemt_me_idle_close_by_peer_total 6961
telemt_me_route_drop_no_conn_total 1739278
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2061115
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7306
telemt_desync_full_logged_total 2431
telemt_desync_suppressed_total 4875
telemt_desync_frames_bucket_total{bucket="1_2"} 1554
telemt_desync_frames_bucket_total{bucket="3_10"} 2865
telemt_desync_frames_bucket_total{bucket="gt_10"} 2887
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7011
telemt_me_refill_failed_total 128
telemt_me_writer_restored_same_endpoint_total 6516
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 471
telemt_user_connections_total{user="hello"} 2067218
telemt_user_connections_current{user="hello"} 2954
telemt_user_octets_from_client{user="hello"} 23119524128 (21.53 GB)
telemt_user_octets_to_client{user="hello"} 554698544398 (516.60 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 983
telemt_user_unique_ips_recent_window{user="hello"} 469
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 50564.4 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3094158
telemt_connections_bad_total 667319
telemt_connections_current 3352
telemt_connections_me_current 3352
telemt_handshake_timeouts_total 62533
telemt_upstream_connect_attempt_total 9072
telemt_upstream_connect_success_total 9006
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 9072
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4654
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4316
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 19
telemt_me_reconnect_attempts_total 7641
telemt_me_reconnect_success_total 6434
telemt_me_reader_eof_total 6833
telemt_me_idle_close_by_peer_total 6832
telemt_me_route_drop_no_conn_total 1220931
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2058096
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8894
telemt_desync_full_logged_total 2766
telemt_desync_suppressed_total 6128
telemt_desync_frames_bucket_total{bucket="1_2"} 1669
telemt_desync_frames_bucket_total{bucket="3_10"} 3846
telemt_desync_frames_bucket_total{bucket="gt_10"} 3379
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 6566
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 6410
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 132
telemt_user_connections_total{user="hello"} 2056649
telemt_user_connections_current{user="hello"} 3352
telemt_user_octets_from_client{user="hello"} 35178507364 (32.76 GB)
telemt_user_octets_to_client{user="hello"} 819517514184 (763.24 GB)
telemt_user_unique_ips_current{user="hello"} 1183
telemt_user_unique_ips_recent_window{user="hello"} 552
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 50576.5 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 536301
telemt_connections_bad_total 18885
telemt_connections_current 1020
telemt_connections_me_current 1020
telemt_handshake_timeouts_total 4163
telemt_upstream_connect_attempt_total 12493
telemt_upstream_connect_success_total 12169
telemt_upstream_connect_fail_total 324
telemt_upstream_connect_attempts_per_request{bucket="1"} 12493
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5988
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6179
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 324
telemt_me_keepalive_timeout_total 22
telemt_me_reconnect_attempts_total 17186
telemt_me_reconnect_success_total 9594
telemt_me_reader_eof_total 10231
telemt_me_idle_close_by_peer_total 10231
telemt_me_route_drop_no_conn_total 278158
telemt_me_route_drop_channel_closed_total 35
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 487239
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1081
telemt_desync_full_logged_total 376
telemt_desync_suppressed_total 705
telemt_desync_frames_bucket_total{bucket="1_2"} 220
telemt_desync_frames_bucket_total{bucket="3_10"} 439
telemt_desync_frames_bucket_total{bucket="gt_10"} 422
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 9922
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9563
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 328
telemt_user_connections_total{user="hello"} 487172
telemt_user_connections_current{user="hello"} 1020
telemt_user_octets_from_client{user="hello"} 7822354036 (7.29 GB)
telemt_user_octets_to_client{user="hello"} 177148545844 (164.98 GB)
telemt_user_unique_ips_current{user="hello"} 362
telemt_user_unique_ips_recent_window{user="hello"} 170
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 50567.0 (14h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2163466
telemt_connections_bad_total 177200
telemt_connections_current 3270
telemt_connections_me_current 3270
telemt_handshake_timeouts_total 73141
telemt_upstream_connect_attempt_total 10171
telemt_upstream_connect_success_total 10170
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10171
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5521
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4646
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 86
telemt_me_reconnect_attempts_total 8947
telemt_me_reconnect_success_total 7577
telemt_me_reader_eof_total 8016
telemt_me_idle_close_by_peer_total 8015
telemt_me_route_drop_no_conn_total 1084337
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1810523
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9876
telemt_desync_full_logged_total 3183
telemt_desync_suppressed_total 6693
telemt_desync_frames_bucket_total{bucket="1_2"} 1889
telemt_desync_frames_bucket_total{bucket="3_10"} 3748
telemt_desync_frames_bucket_total{bucket="gt_10"} 4239
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 7719
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 7562
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 142
telemt_user_connections_total{user="hello"} 1809257
telemt_user_connections_current{user="hello"} 3270
telemt_user_octets_from_client{user="hello"} 23796052348 (22.16 GB)
telemt_user_octets_to_client{user="hello"} 804507979168 (749.26 GB)
telemt_user_unique_ips_current{user="hello"} 1020
telemt_user_unique_ips_recent_window{user="hello"} 444
```