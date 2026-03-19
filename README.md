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

# Server Metrics 2026-03-19 12:22:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 52422.5 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1301729
telemt_connections_bad_total 104995
telemt_connections_current 1667
telemt_connections_me_current 1667
telemt_handshake_timeouts_total 46439
telemt_upstream_connect_attempt_total 10119
telemt_upstream_connect_success_total 9948
telemt_upstream_connect_fail_total 171
telemt_upstream_connect_attempts_per_request{bucket="1"} 10119
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4868
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5077
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 171
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 96
telemt_me_reconnect_attempts_total 9187
telemt_me_reconnect_success_total 7294
telemt_me_reader_eof_total 7715
telemt_me_idle_close_by_peer_total 7712
telemt_me_seq_mismatch_total 12
telemt_me_route_drop_no_conn_total 540921
telemt_me_route_drop_channel_closed_total 233
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1026287
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5670
telemt_desync_full_logged_total 1749
telemt_desync_suppressed_total 3921
telemt_desync_frames_bucket_total{bucket="1_2"} 1797
telemt_desync_frames_bucket_total{bucket="3_10"} 2044
telemt_desync_frames_bucket_total{bucket="gt_10"} 1829
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 7458
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 7272
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 164
telemt_user_connections_total{user="hello"} 1020098
telemt_user_connections_current{user="hello"} 1667
telemt_user_octets_from_client{user="hello"} 16012787568 (14.91 GB)
telemt_user_octets_to_client{user="hello"} 308672544648 (287.47 GB)
telemt_user_unique_ips_current{user="hello"} 603
telemt_user_unique_ips_recent_window{user="hello"} 247
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 52427.2 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3693959
telemt_connections_bad_total 235018
telemt_connections_current 4139
telemt_connections_me_current 4139
telemt_handshake_timeouts_total 64130
telemt_upstream_connect_attempt_total 9792
telemt_upstream_connect_success_total 9608
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 9792
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4870
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4707
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 18328
telemt_me_reconnect_success_total 6917
telemt_me_reader_eof_total 7588
telemt_me_idle_close_by_peer_total 7587
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 3117805
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3120356
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 37
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11934
telemt_desync_full_logged_total 3990
telemt_desync_suppressed_total 7944
telemt_desync_frames_bucket_total{bucket="1_2"} 2310
telemt_desync_frames_bucket_total{bucket="3_10"} 4670
telemt_desync_frames_bucket_total{bucket="gt_10"} 4954
telemt_pool_swap_total 34
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7396
telemt_me_refill_failed_total 356
telemt_me_writer_restored_same_endpoint_total 6892
telemt_me_writer_restored_fallback_total 25
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 479
telemt_user_connections_total{user="hello"} 3119962
telemt_user_connections_current{user="hello"} 4139
telemt_user_octets_from_client{user="hello"} 38909054816 (36.24 GB)
telemt_user_octets_to_client{user="hello"} 885588439900 (824.77 GB)
telemt_user_unique_ips_current{user="hello"} 1299
telemt_user_unique_ips_recent_window{user="hello"} 640
```

## koara.io

Не удалось получить метрики для этого сервера.

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 52477.4 (14h 34m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2835440
telemt_connections_bad_total 144457
telemt_connections_current 3333
telemt_connections_me_current 3333
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 67746
telemt_upstream_connect_attempt_total 24654
telemt_upstream_connect_success_total 24131
telemt_upstream_connect_fail_total 523
telemt_upstream_connect_attempts_per_request{bucket="1"} 24654
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17882
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5813
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 434
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 523
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 11578
telemt_me_reconnect_success_total 6763
telemt_me_reader_eof_total 7183
telemt_me_idle_close_by_peer_total 7182
telemt_me_route_drop_no_conn_total 1912105
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2214050
telemt_me_writer_pick_total{mode="p2c",result="full"} 113
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_writer_pick_blocking_fallback_total 103
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7737
telemt_desync_full_logged_total 2577
telemt_desync_suppressed_total 5160
telemt_desync_frames_bucket_total{bucket="1_2"} 1623
telemt_desync_frames_bucket_total{bucket="3_10"} 3049
telemt_desync_frames_bucket_total{bucket="gt_10"} 3065
telemt_pool_swap_total 41
telemt_me_writer_removed_unexpected_total 7378
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6739
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 311
telemt_me_writer_removed_unexpected_minus_restored_total 615
telemt_user_connections_total{user="hello"} 2226555
telemt_user_connections_current{user="hello"} 3333
telemt_user_octets_from_client{user="hello"} 24821948956 (23.12 GB)
telemt_user_octets_to_client{user="hello"} 582351540169 (542.36 GB)
telemt_user_msgs_from_client{user="hello"} 46376
telemt_user_msgs_to_client{user="hello"} 105213
telemt_user_unique_ips_current{user="hello"} 1088
telemt_user_unique_ips_recent_window{user="hello"} 612
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 52420.9 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3451944
telemt_connections_bad_total 716402
telemt_connections_current 3651
telemt_connections_me_current 3651
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 67091
telemt_upstream_connect_attempt_total 61236
telemt_upstream_connect_success_total 58757
telemt_upstream_connect_fail_total 2479
telemt_upstream_connect_attempts_per_request{bucket="1"} 61236
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 51029
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6715
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2479
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 115
telemt_me_reconnect_attempts_total 69990
telemt_me_reconnect_success_total 6942
telemt_me_reader_eof_total 7250
telemt_me_idle_close_by_peer_total 7247
telemt_me_route_drop_no_conn_total 1543717
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2279877
telemt_me_writer_pick_total{mode="p2c",result="full"} 8278
telemt_me_writer_pick_total{mode="p2c",result="closed"} 806
telemt_me_writer_pick_blocking_fallback_total 9050
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9590
telemt_desync_full_logged_total 2984
telemt_desync_suppressed_total 6606
telemt_desync_frames_bucket_total{bucket="1_2"} 1793
telemt_desync_frames_bucket_total{bucket="3_10"} 4122
telemt_desync_frames_bucket_total{bucket="gt_10"} 3675
telemt_pool_swap_total 45
telemt_me_writer_removed_unexpected_total 7056
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 6918
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 114
telemt_user_connections_total{user="hello"} 2328777
telemt_user_connections_current{user="hello"} 3651
telemt_user_octets_from_client{user="hello"} 37282245255 (34.72 GB)
telemt_user_octets_to_client{user="hello"} 857305994956 (798.43 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1130
telemt_user_unique_ips_recent_window{user="hello"} 591
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 52433.9 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 574676
telemt_connections_bad_total 19838
telemt_connections_current 996
telemt_connections_me_current 996
telemt_handshake_timeouts_total 4726
telemt_upstream_connect_attempt_total 12995
telemt_upstream_connect_success_total 12650
telemt_upstream_connect_fail_total 345
telemt_upstream_connect_attempts_per_request{bucket="1"} 12995
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6203
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6443
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 345
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 17575
telemt_me_reconnect_success_total 9982
telemt_me_reader_eof_total 10635
telemt_me_idle_close_by_peer_total 10635
telemt_me_route_drop_no_conn_total 298406
telemt_me_route_drop_channel_closed_total 43
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 522492
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1304
telemt_desync_full_logged_total 451
telemt_desync_suppressed_total 853
telemt_desync_frames_bucket_total{bucket="1_2"} 255
telemt_desync_frames_bucket_total{bucket="3_10"} 532
telemt_desync_frames_bucket_total{bucket="gt_10"} 517
telemt_pool_swap_total 25
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 10312
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9951
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 330
telemt_user_connections_total{user="hello"} 522422
telemt_user_connections_current{user="hello"} 996
telemt_user_octets_from_client{user="hello"} 8390541464 (7.81 GB)
telemt_user_octets_to_client{user="hello"} 187082546632 (174.23 GB)
telemt_user_unique_ips_current{user="hello"} 360
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 52423.2 (14h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2304586
telemt_connections_bad_total 184703
telemt_connections_current 3196
telemt_connections_me_current 3196
telemt_handshake_timeouts_total 74518
telemt_upstream_connect_attempt_total 10620
telemt_upstream_connect_success_total 10619
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10620
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 10441
telemt_me_reconnect_success_total 7933
telemt_me_reader_eof_total 8419
telemt_me_idle_close_by_peer_total 8418
telemt_me_route_drop_no_conn_total 1185351
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1939203
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 23
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10609
telemt_desync_full_logged_total 3367
telemt_desync_suppressed_total 7242
telemt_desync_frames_bucket_total{bucket="1_2"} 2040
telemt_desync_frames_bucket_total{bucket="3_10"} 4016
telemt_desync_frames_bucket_total{bucket="gt_10"} 4553
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 8112
telemt_me_refill_failed_total 77
telemt_me_writer_restored_same_endpoint_total 7918
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 179
telemt_user_connections_total{user="hello"} 1937941
telemt_user_connections_current{user="hello"} 3196
telemt_user_octets_from_client{user="hello"} 25273558308 (23.54 GB)
telemt_user_octets_to_client{user="hello"} 856410622876 (797.59 GB)
telemt_user_unique_ips_current{user="hello"} 1014
telemt_user_unique_ips_recent_window{user="hello"} 445
```