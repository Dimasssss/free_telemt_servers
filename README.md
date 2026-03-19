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

# Server Metrics 2026-03-19 12:17:04 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 52116.6 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1290554
telemt_connections_bad_total 104722
telemt_connections_current 1721
telemt_connections_me_current 1721
telemt_handshake_timeouts_total 45767
telemt_upstream_connect_attempt_total 10005
telemt_upstream_connect_success_total 9836
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 10005
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4817
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5016
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 95
telemt_me_reconnect_attempts_total 9118
telemt_me_reconnect_success_total 7226
telemt_me_reader_eof_total 7638
telemt_me_idle_close_by_peer_total 7635
telemt_me_seq_mismatch_total 11
telemt_me_route_drop_no_conn_total 537119
telemt_me_route_drop_channel_closed_total 228
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1016284
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 35
telemt_me_endpoint_quarantine_total 33
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5614
telemt_desync_full_logged_total 1728
telemt_desync_suppressed_total 3886
telemt_desync_frames_bucket_total{bucket="1_2"} 1783
telemt_desync_frames_bucket_total{bucket="3_10"} 2024
telemt_desync_frames_bucket_total{bucket="gt_10"} 1807
telemt_pool_swap_total 40
telemt_pool_stale_pick_total 3
telemt_me_writer_removed_unexpected_total 7389
telemt_me_refill_failed_total 58
telemt_me_writer_restored_same_endpoint_total 7205
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 163
telemt_user_connections_total{user="hello"} 1010153
telemt_user_connections_current{user="hello"} 1721
telemt_user_octets_from_client{user="hello"} 15816865392 (14.73 GB)
telemt_user_octets_to_client{user="hello"} 304952803824 (284.01 GB)
telemt_user_unique_ips_current{user="hello"} 597
telemt_user_unique_ips_recent_window{user="hello"} 272
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 52121.2 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3663541
telemt_connections_bad_total 234191
telemt_connections_current 3820
telemt_connections_me_current 3820
telemt_handshake_timeouts_total 63901
telemt_upstream_connect_attempt_total 9703
telemt_upstream_connect_success_total 9521
telemt_upstream_connect_fail_total 182
telemt_upstream_connect_attempts_per_request{bucket="1"} 9703
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4824
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4666
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 31
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 182
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 18236
telemt_me_reconnect_success_total 6874
telemt_me_reader_eof_total 7544
telemt_me_idle_close_by_peer_total 7543
telemt_me_seq_mismatch_total 14
telemt_me_route_drop_no_conn_total 3100539
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3092472
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 36
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11840
telemt_desync_full_logged_total 3965
telemt_desync_suppressed_total 7875
telemt_desync_frames_bucket_total{bucket="1_2"} 2291
telemt_desync_frames_bucket_total{bucket="3_10"} 4645
telemt_desync_frames_bucket_total{bucket="gt_10"} 4904
telemt_pool_swap_total 33
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 7351
telemt_me_refill_failed_total 354
telemt_me_writer_restored_same_endpoint_total 6851
telemt_me_writer_restored_fallback_total 23
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 477
telemt_user_connections_total{user="hello"} 3092082
telemt_user_connections_current{user="hello"} 3820
telemt_user_octets_from_client{user="hello"} 38641704324 (35.99 GB)
telemt_user_octets_to_client{user="hello"} 875820063400 (815.67 GB)
telemt_user_unique_ips_current{user="hello"} 1277
telemt_user_unique_ips_recent_window{user="hello"} 562
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 52118.8 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2754160
telemt_connections_bad_total 318418
telemt_connections_current 3115
telemt_connections_me_current 3115
telemt_handshake_timeouts_total 53669
telemt_upstream_connect_attempt_total 9455
telemt_upstream_connect_success_total 9455
telemt_upstream_connect_attempts_per_request{bucket="1"} 9455
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4922
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4515
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 15
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 9162
telemt_me_reconnect_success_total 6808
telemt_me_reader_eof_total 7242
telemt_me_idle_close_by_peer_total 7240
telemt_me_route_drop_no_conn_total 1760464
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2176908
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8982
telemt_desync_full_logged_total 2819
telemt_desync_suppressed_total 6163
telemt_desync_frames_bucket_total{bucket="1_2"} 2055
telemt_desync_frames_bucket_total{bucket="3_10"} 3281
telemt_desync_frames_bucket_total{bucket="gt_10"} 3646
telemt_pool_swap_total 42
telemt_me_writer_removed_unexpected_total 6995
telemt_me_refill_failed_total 72
telemt_me_writer_restored_same_endpoint_total 6792
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 187
telemt_user_connections_total{user="hello"} 2174519
telemt_user_connections_current{user="hello"} 3115
telemt_user_octets_from_client{user="hello"} 29512754672 (27.49 GB)
telemt_user_octets_to_client{user="hello"} 908791723680 (846.38 GB)
telemt_user_unique_ips_current{user="hello"} 1078
telemt_user_unique_ips_recent_window{user="hello"} 460
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 52171.8 (14h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2794557
telemt_connections_bad_total 143662
telemt_connections_current 2988
telemt_connections_me_current 2988
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 67463
telemt_upstream_connect_attempt_total 24561
telemt_upstream_connect_success_total 24039
telemt_upstream_connect_fail_total 522
telemt_upstream_connect_attempts_per_request{bucket="1"} 24561
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17835
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5769
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 522
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 11529
telemt_me_reconnect_success_total 6714
telemt_me_reader_eof_total 7138
telemt_me_idle_close_by_peer_total 7137
telemt_me_route_drop_no_conn_total 1830178
telemt_me_route_drop_channel_closed_total 23
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2175473
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7661
telemt_desync_full_logged_total 2550
telemt_desync_suppressed_total 5111
telemt_desync_frames_bucket_total{bucket="1_2"} 1603
telemt_desync_frames_bucket_total{bucket="3_10"} 3024
telemt_desync_frames_bucket_total{bucket="gt_10"} 3034
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 7336
telemt_me_refill_failed_total 138
telemt_me_writer_restored_same_endpoint_total 6690
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 295
telemt_me_writer_removed_unexpected_minus_restored_total 622
telemt_user_connections_total{user="hello"} 2188062
telemt_user_connections_current{user="hello"} 2988
telemt_user_octets_from_client{user="hello"} 24438634504 (22.76 GB)
telemt_user_octets_to_client{user="hello"} 578155077913 (538.45 GB)
telemt_user_msgs_from_client{user="hello"} 46376
telemt_user_msgs_to_client{user="hello"} 105213
telemt_user_unique_ips_current{user="hello"} 996
telemt_user_unique_ips_recent_window{user="hello"} 794
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 52115.5 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3423723
telemt_connections_bad_total 715280
telemt_connections_current 3822
telemt_connections_me_current 3822
telemt_relay_adaptive_promotions_total 22
telemt_relay_adaptive_demotions_total 1819
telemt_relay_adaptive_hard_promotions_total 20
telemt_handshake_timeouts_total 66364
telemt_upstream_connect_attempt_total 61137
telemt_upstream_connect_success_total 58660
telemt_upstream_connect_fail_total 2477
telemt_upstream_connect_attempts_per_request{bucket="1"} 61137
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 50980
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1011
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 2477
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 81
telemt_me_reconnect_attempts_total 69936
telemt_me_reconnect_success_total 6888
telemt_me_reader_eof_total 7184
telemt_me_idle_close_by_peer_total 7181
telemt_me_route_drop_no_conn_total 1531474
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2256391
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
telemt_desync_total 9427
telemt_desync_full_logged_total 2941
telemt_desync_suppressed_total 6486
telemt_desync_frames_bucket_total{bucket="1_2"} 1772
telemt_desync_frames_bucket_total{bucket="3_10"} 4055
telemt_desync_frames_bucket_total{bucket="gt_10"} 3600
telemt_pool_swap_total 44
telemt_me_writer_removed_unexpected_total 6999
telemt_me_refill_failed_total 1967
telemt_me_writer_restored_same_endpoint_total 6864
telemt_me_writer_restored_fallback_total 24
telemt_me_no_writer_failfast_total 1478
telemt_me_async_recovery_trigger_total 7229
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 2305297
telemt_user_connections_current{user="hello"} 3818
telemt_user_octets_from_client{user="hello"} 37031769831 (34.49 GB)
telemt_user_octets_to_client{user="hello"} 850036529568 (791.66 GB)
telemt_user_msgs_from_client{user="hello"} 549175
telemt_user_msgs_to_client{user="hello"} 1884577
telemt_user_unique_ips_current{user="hello"} 1112
telemt_user_unique_ips_recent_window{user="hello"} 541
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 52127.0 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 568914
telemt_connections_bad_total 19694
telemt_connections_current 1013
telemt_connections_me_current 1013
telemt_handshake_timeouts_total 4582
telemt_upstream_connect_attempt_total 12870
telemt_upstream_connect_success_total 12534
telemt_upstream_connect_fail_total 336
telemt_upstream_connect_attempts_per_request{bucket="1"} 12870
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6155
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6377
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 336
telemt_me_keepalive_timeout_total 38
telemt_me_reconnect_attempts_total 17502
telemt_me_reconnect_success_total 9909
telemt_me_reader_eof_total 10548
telemt_me_idle_close_by_peer_total 10548
telemt_me_route_drop_no_conn_total 295293
telemt_me_route_drop_channel_closed_total 42
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 517230
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 4
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1279
telemt_desync_full_logged_total 444
telemt_desync_suppressed_total 835
telemt_desync_frames_bucket_total{bucket="1_2"} 250
telemt_desync_frames_bucket_total{bucket="3_10"} 521
telemt_desync_frames_bucket_total{bucket="gt_10"} 508
telemt_pool_swap_total 24
telemt_pool_stale_pick_total 194
telemt_me_writer_removed_unexpected_total 10238
telemt_me_refill_failed_total 235
telemt_me_writer_restored_same_endpoint_total 9878
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 329
telemt_user_connections_total{user="hello"} 517164
telemt_user_connections_current{user="hello"} 1013
telemt_user_octets_from_client{user="hello"} 8339658928 (7.77 GB)
telemt_user_octets_to_client{user="hello"} 186189288828 (173.40 GB)
telemt_user_unique_ips_current{user="hello"} 350
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 52117.4 (14h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2284937
telemt_connections_bad_total 183656
telemt_connections_current 3009
telemt_connections_me_current 3009
telemt_handshake_timeouts_total 74130
telemt_upstream_connect_attempt_total 10515
telemt_upstream_connect_success_total 10514
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 10515
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5694
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4817
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 94
telemt_me_reconnect_attempts_total 10364
telemt_me_reconnect_success_total 7872
telemt_me_reader_eof_total 8346
telemt_me_idle_close_by_peer_total 8345
telemt_me_route_drop_no_conn_total 1177423
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1921540
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10493
telemt_desync_full_logged_total 3339
telemt_desync_suppressed_total 7154
telemt_desync_frames_bucket_total{bucket="1_2"} 2008
telemt_desync_frames_bucket_total{bucket="3_10"} 3981
telemt_desync_frames_bucket_total{bucket="gt_10"} 4504
telemt_pool_swap_total 43
telemt_me_writer_removed_unexpected_total 8050
telemt_me_refill_failed_total 76
telemt_me_writer_restored_same_endpoint_total 7857
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 1920287
telemt_user_connections_current{user="hello"} 3009
telemt_user_octets_from_client{user="hello"} 24983273156 (23.27 GB)
telemt_user_octets_to_client{user="hello"} 849674943328 (791.32 GB)
telemt_user_unique_ips_current{user="hello"} 1006
telemt_user_unique_ips_recent_window{user="hello"} 444
```