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

# Server Metrics 2026-03-19 09:02:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.23

telemt_uptime_seconds 40431.6 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 800249
telemt_connections_bad_total 77941
telemt_connections_current 1695
telemt_connections_me_current 1695
telemt_handshake_timeouts_total 32951
telemt_upstream_connect_attempt_total 7634
telemt_upstream_connect_success_total 7501
telemt_upstream_connect_fail_total 133
telemt_upstream_connect_attempts_per_request{bucket="1"} 7634
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3864
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 133
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 83
telemt_me_reconnect_attempts_total 6646
telemt_me_reconnect_success_total 5492
telemt_me_reader_eof_total 5820
telemt_me_idle_close_by_peer_total 5819
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 240143
telemt_me_route_drop_channel_closed_total 97
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 614679
telemt_me_writer_pick_total{mode="p2c",result="full"} 14
telemt_me_writer_pick_total{mode="p2c",result="closed"} 33
telemt_me_endpoint_quarantine_total 29
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3910
telemt_desync_full_logged_total 1162
telemt_desync_suppressed_total 2748
telemt_desync_frames_bucket_total{bucket="1_2"} 1311
telemt_desync_frames_bucket_total{bucket="3_10"} 1438
telemt_desync_frames_bucket_total{bucket="gt_10"} 1161
telemt_pool_swap_total 35
telemt_me_writer_removed_unexpected_total 5590
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 5473
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 136
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 611284
telemt_user_connections_current{user="hello"} 1695
telemt_user_octets_from_client{user="hello"} 9900825260 (9.22 GB)
telemt_user_octets_to_client{user="hello"} 203083203056 (189.14 GB)
telemt_user_unique_ips_current{user="hello"} 555
telemt_user_unique_ips_recent_window{user="hello"} 322
```

## psb.hosting

```
telemt 3.3.23

telemt_uptime_seconds 40436.6 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1964330
telemt_connections_bad_total 107284
telemt_connections_current 4446
telemt_connections_me_current 4446
telemt_handshake_timeouts_total 44288
telemt_upstream_connect_attempt_total 7656
telemt_upstream_connect_success_total 7514
telemt_upstream_connect_fail_total 142
telemt_upstream_connect_attempts_per_request{bucket="1"} 7656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3740
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3754
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 20
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 142
telemt_me_keepalive_timeout_total 34
telemt_me_reconnect_attempts_total 6646
telemt_me_reconnect_success_total 5485
telemt_me_reader_eof_total 5801
telemt_me_idle_close_by_peer_total 5801
telemt_me_seq_mismatch_total 13
telemt_me_route_drop_no_conn_total 854601
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1629946
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 35
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7202
telemt_desync_full_logged_total 2453
telemt_desync_suppressed_total 4749
telemt_desync_frames_bucket_total{bucket="1_2"} 1293
telemt_desync_frames_bucket_total{bucket="3_10"} 2770
telemt_desync_frames_bucket_total{bucket="gt_10"} 3139
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 1
telemt_me_writer_removed_unexpected_total 5619
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 5463
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 756
telemt_me_writer_removed_unexpected_minus_restored_total 134
telemt_user_connections_total{user="hello"} 1629707
telemt_user_connections_current{user="hello"} 4446
telemt_user_octets_from_client{user="hello"} 27421295980 (25.54 GB)
telemt_user_octets_to_client{user="hello"} 612425456124 (570.37 GB)
telemt_user_unique_ips_current{user="hello"} 1491
telemt_user_unique_ips_recent_window{user="hello"} 797
```

## koara.io

```
telemt 3.3.23

telemt_uptime_seconds 40433.8 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1662056
telemt_connections_bad_total 206393
telemt_connections_current 3596
telemt_connections_me_current 3596
telemt_handshake_timeouts_total 40893
telemt_upstream_connect_attempt_total 7179
telemt_upstream_connect_success_total 7179
telemt_upstream_connect_attempts_per_request{bucket="1"} 7179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3750
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3417
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 3
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_timeout_total 18
telemt_me_reconnect_attempts_total 5181
telemt_me_reconnect_success_total 5150
telemt_me_reader_eof_total 5457
telemt_me_idle_close_by_peer_total 5457
telemt_me_route_drop_no_conn_total 757663
telemt_me_route_drop_channel_closed_total 55
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1282469
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 5914
telemt_desync_full_logged_total 1846
telemt_desync_suppressed_total 4068
telemt_desync_frames_bucket_total{bucket="1_2"} 1335
telemt_desync_frames_bucket_total{bucket="3_10"} 2143
telemt_desync_frames_bucket_total{bucket="gt_10"} 2436
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 5244
telemt_me_writer_restored_same_endpoint_total 5134
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 162
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 1281945
telemt_user_connections_current{user="hello"} 3596
telemt_user_octets_from_client{user="hello"} 20596060940 (19.18 GB)
telemt_user_octets_to_client{user="hello"} 612555108144 (570.49 GB)
telemt_user_unique_ips_current{user="hello"} 1135
telemt_user_unique_ips_recent_window{user="hello"} 599
```

## landvps.ru

```
telemt 3.3.23

telemt_uptime_seconds 40486.9 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1718890
telemt_connections_bad_total 98310
telemt_connections_current 3229
telemt_connections_me_current 3229
telemt_relay_adaptive_promotions_total 1
telemt_relay_adaptive_hard_promotions_total 1
telemt_handshake_timeouts_total 44508
telemt_upstream_connect_attempt_total 15405
telemt_upstream_connect_success_total 15303
telemt_upstream_connect_fail_total 102
telemt_upstream_connect_attempts_per_request{bucket="1"} 15405
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 10955
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4199
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 147
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 102
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7519
telemt_me_reconnect_success_total 5123
telemt_me_reader_eof_total 5447
telemt_me_idle_close_by_peer_total 5446
telemt_me_route_drop_no_conn_total 793367
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1251480
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4633
telemt_desync_full_logged_total 1583
telemt_desync_suppressed_total 3050
telemt_desync_frames_bucket_total{bucket="1_2"} 927
telemt_desync_frames_bucket_total{bucket="3_10"} 1823
telemt_desync_frames_bucket_total{bucket="gt_10"} 1883
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 5384
telemt_me_refill_failed_total 70
telemt_me_writer_restored_same_endpoint_total 5099
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 272
telemt_me_writer_removed_unexpected_minus_restored_total 261
telemt_user_connections_total{user="hello"} 1258257
telemt_user_connections_current{user="hello"} 3229
telemt_user_octets_from_client{user="hello"} 15753194448 (14.67 GB)
telemt_user_octets_to_client{user="hello"} 385013838746 (358.57 GB)
telemt_user_msgs_from_client{user="hello"} 28643
telemt_user_msgs_to_client{user="hello"} 76631
telemt_user_unique_ips_current{user="hello"} 1069
telemt_user_unique_ips_recent_window{user="hello"} 923
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 40430.3 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2033012
telemt_connections_bad_total 514531
telemt_connections_current 3872
telemt_connections_me_current 3872
telemt_handshake_timeouts_total 42643
telemt_upstream_connect_attempt_total 6913
telemt_upstream_connect_success_total 6864
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 6913
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3485
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3358
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 21
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 4885
telemt_me_reconnect_success_total 4844
telemt_me_reader_eof_total 5137
telemt_me_idle_close_by_peer_total 5137
telemt_me_route_drop_no_conn_total 550564
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1274086
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6140
telemt_desync_full_logged_total 1913
telemt_desync_suppressed_total 4227
telemt_desync_frames_bucket_total{bucket="1_2"} 1242
telemt_desync_frames_bucket_total{bucket="3_10"} 2726
telemt_desync_frames_bucket_total{bucket="gt_10"} 2172
telemt_pool_swap_total 40
telemt_me_writer_removed_unexpected_total 4916
telemt_me_writer_restored_same_endpoint_total 4820
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 377
telemt_me_writer_removed_unexpected_minus_restored_total 72
telemt_user_connections_total{user="hello"} 1273339
telemt_user_connections_current{user="hello"} 3873
telemt_user_octets_from_client{user="hello"} 24717448568 (23.02 GB)
telemt_user_octets_to_client{user="hello"} 579038287352 (539.27 GB)
telemt_user_unique_ips_current{user="hello"} 1252
telemt_user_unique_ips_recent_window{user="hello"} 721
```

## hostvds.com

```
telemt 3.3.23

telemt_uptime_seconds 40442.2 (11h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 354970
telemt_connections_bad_total 16592
telemt_connections_current 905
telemt_connections_me_current 905
telemt_handshake_timeouts_total 2977
telemt_upstream_connect_attempt_total 10247
telemt_upstream_connect_success_total 9983
telemt_upstream_connect_fail_total 264
telemt_upstream_connect_attempts_per_request{bucket="1"} 10247
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4949
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5033
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 264
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 13343
telemt_me_reconnect_success_total 7961
telemt_me_reader_eof_total 8454
telemt_me_idle_close_by_peer_total 8454
telemt_me_route_drop_no_conn_total 167399
telemt_me_route_drop_channel_closed_total 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 316707
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 490
telemt_desync_full_logged_total 170
telemt_desync_suppressed_total 320
telemt_desync_frames_bucket_total{bucket="1_2"} 135
telemt_desync_frames_bucket_total{bucket="3_10"} 195
telemt_desync_frames_bucket_total{bucket="gt_10"} 160
telemt_pool_swap_total 20
telemt_pool_stale_pick_total 193
telemt_me_writer_removed_unexpected_total 8188
telemt_me_refill_failed_total 167
telemt_me_writer_restored_same_endpoint_total 7931
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 138
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 316672
telemt_user_connections_current{user="hello"} 905
telemt_user_octets_from_client{user="hello"} 4577458616 (4.26 GB)
telemt_user_octets_to_client{user="hello"} 133935195480 (124.74 GB)
telemt_user_unique_ips_current{user="hello"} 340
telemt_user_unique_ips_recent_window{user="hello"} 219
```

## 4vps.su

```
telemt 3.3.23

telemt_uptime_seconds 40432.7 (11h 13m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1364015
telemt_connections_bad_total 122164
telemt_connections_current 3307
telemt_connections_me_current 3307
telemt_handshake_timeouts_total 59883
telemt_upstream_connect_attempt_total 8133
telemt_upstream_connect_success_total 8132
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 8133
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4345
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3784
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 42
telemt_me_reconnect_attempts_total 7455
telemt_me_reconnect_success_total 6109
telemt_me_reader_eof_total 6473
telemt_me_idle_close_by_peer_total 6472
telemt_me_route_drop_no_conn_total 531615
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1129654
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 6530
telemt_desync_full_logged_total 2147
telemt_desync_suppressed_total 4383
telemt_desync_frames_bucket_total{bucket="1_2"} 1225
telemt_desync_frames_bucket_total{bucket="3_10"} 2471
telemt_desync_frames_bucket_total{bucket="gt_10"} 2834
telemt_pool_swap_total 38
telemt_me_writer_removed_unexpected_total 6221
telemt_me_refill_failed_total 41
telemt_me_writer_restored_same_endpoint_total 6094
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 166
telemt_me_writer_removed_unexpected_minus_restored_total 112
telemt_user_connections_total{user="hello"} 1128558
telemt_user_connections_current{user="hello"} 3307
telemt_user_octets_from_client{user="hello"} 15594511896 (14.52 GB)
telemt_user_octets_to_client{user="hello"} 561054996076 (522.52 GB)
telemt_user_unique_ips_current{user="hello"} 1069
telemt_user_unique_ips_recent_window{user="hello"} 587
```