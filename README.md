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

# Server Metrics 2026-03-17 13:27:43 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 67347.4 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 666302
telemt_connections_bad_total 5295
telemt_handshake_timeouts_total 20281
telemt_upstream_connect_attempt_total 16639
telemt_upstream_connect_success_total 16187
telemt_upstream_connect_fail_total 452
telemt_upstream_connect_attempts_per_request{bucket="1"} 16639
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8447
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7590
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 452
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 120
telemt_me_reconnect_attempts_total 15728
telemt_me_reconnect_success_total 10540
telemt_me_reader_eof_total 11258
telemt_me_idle_close_by_peer_total 11257
telemt_me_route_drop_no_conn_total 223429
telemt_me_route_drop_channel_closed_total 69
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 602987
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4425
telemt_desync_full_logged_total 1221
telemt_desync_suppressed_total 3204
telemt_desync_frames_bucket_total{bucket="1_2"} 1267
telemt_desync_frames_bucket_total{bucket="3_10"} 1819
telemt_desync_frames_bucket_total{bucket="gt_10"} 1339
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10853
telemt_me_refill_failed_total 157
telemt_me_writer_restored_same_endpoint_total 10518
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 313
telemt_user_connections_total{user="hello"} 604876
telemt_user_connections_current{user="hello"} 1012
telemt_user_octets_from_client{user="hello"} 9177418319 (8.55 GB)
telemt_user_octets_to_client{user="hello"} 213712058087 (199.03 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 320
telemt_user_unique_ips_recent_window{user="hello"} 155
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 67599.5 (18h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 406794
telemt_connections_bad_total 24236
telemt_handshake_timeouts_total 20933
telemt_upstream_connect_attempt_total 17894
telemt_upstream_connect_success_total 17617
telemt_upstream_connect_fail_total 277
telemt_upstream_connect_attempts_per_request{bucket="1"} 17894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7985
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9181
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 451
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 277
telemt_me_keepalive_timeout_total 260
telemt_me_reconnect_attempts_total 27646
telemt_me_reconnect_success_total 13250
telemt_me_reader_eof_total 14275
telemt_me_idle_close_by_peer_total 14275
telemt_me_route_drop_no_conn_total 171530
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 339748
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1326
telemt_desync_full_logged_total 428
telemt_desync_suppressed_total 898
telemt_desync_frames_bucket_total{bucket="1_2"} 286
telemt_desync_frames_bucket_total{bucket="3_10"} 591
telemt_desync_frames_bucket_total{bucket="gt_10"} 449
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13862
telemt_me_refill_failed_total 446
telemt_me_writer_restored_same_endpoint_total 13234
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 612
telemt_user_connections_total{user="hello"} 340656
telemt_user_connections_current{user="hello"} 515
telemt_user_octets_from_client{user="hello"} 3727164775 (3.47 GB)
telemt_user_octets_to_client{user="hello"} 115769924539 (107.82 GB)
telemt_user_msgs_from_client{user="hello"} 2850
telemt_user_msgs_to_client{user="hello"} 6435
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 67
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 67374.9 (18h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 219106
telemt_connections_bad_total 7758
telemt_handshake_timeouts_total 16647
telemt_upstream_connect_attempt_total 17796
telemt_upstream_connect_success_total 17706
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 17796
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7878
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9753
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_keepalive_timeout_total 28
telemt_me_reconnect_attempts_total 17435
telemt_me_reconnect_success_total 14306
telemt_me_reader_eof_total 15272
telemt_me_idle_close_by_peer_total 15272
telemt_me_route_drop_no_conn_total 77688
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 183299
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 717
telemt_desync_full_logged_total 196
telemt_desync_suppressed_total 521
telemt_desync_frames_bucket_total{bucket="1_2"} 269
telemt_desync_frames_bucket_total{bucket="3_10"} 314
telemt_desync_frames_bucket_total{bucket="gt_10"} 134
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 14603
telemt_me_refill_failed_total 95
telemt_me_writer_restored_same_endpoint_total 14295
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 297
telemt_user_connections_total{user="hello"} 183185
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 15255628596 (14.21 GB)
telemt_user_octets_to_client{user="hello"} 51013784900 (47.51 GB)
telemt_user_unique_ips_current{user="hello"} 110
telemt_user_unique_ips_recent_window{user="hello"} 43
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 67434.2 (18h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 501872
telemt_connections_bad_total 7936
telemt_handshake_timeouts_total 12692
telemt_upstream_connect_attempt_total 16162
telemt_upstream_connect_success_total 16016
telemt_upstream_connect_fail_total 146
telemt_upstream_connect_attempts_per_request{bucket="1"} 16162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7982
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7918
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 107
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 146
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 16918
telemt_me_reconnect_success_total 11613
telemt_me_reader_eof_total 12439
telemt_me_idle_close_by_peer_total 12439
telemt_me_route_drop_no_conn_total 146369
telemt_me_route_drop_channel_closed_total 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 424865
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1513
telemt_desync_full_logged_total 525
telemt_desync_suppressed_total 988
telemt_desync_frames_bucket_total{bucket="1_2"} 370
telemt_desync_frames_bucket_total{bucket="3_10"} 679
telemt_desync_frames_bucket_total{bucket="gt_10"} 464
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11982
telemt_me_refill_failed_total 161
telemt_me_writer_restored_same_endpoint_total 11604
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 369
telemt_user_connections_total{user="hello"} 425726
telemt_user_connections_current{user="hello"} 748
telemt_user_octets_from_client{user="hello"} 5402949610 (5.03 GB)
telemt_user_octets_to_client{user="hello"} 145331328499 (135.35 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 67406.0 (18h 43m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 250765
telemt_connections_bad_total 56176
telemt_handshake_timeouts_total 3244
telemt_upstream_connect_attempt_total 19410
telemt_upstream_connect_success_total 19160
telemt_upstream_connect_fail_total 250
telemt_upstream_connect_attempts_per_request{bucket="1"} 19410
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10378
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 244
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 250
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 32889
telemt_me_reconnect_success_total 15673
telemt_me_reader_eof_total 16847
telemt_me_idle_close_by_peer_total 16847
telemt_me_route_drop_no_conn_total 66120
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 182072
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1080
telemt_desync_full_logged_total 225
telemt_desync_suppressed_total 855
telemt_desync_frames_bucket_total{bucket="1_2"} 540
telemt_desync_frames_bucket_total{bucket="3_10"} 412
telemt_desync_frames_bucket_total{bucket="gt_10"} 128
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 16416
telemt_me_refill_failed_total 535
telemt_me_writer_restored_same_endpoint_total 15665
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 743
telemt_user_connections_total{user="hello"} 182146
telemt_user_connections_current{user="hello"} 325
telemt_user_octets_from_client{user="hello"} 2354962511 (2.19 GB)
telemt_user_octets_to_client{user="hello"} 70339268902 (65.51 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 94
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 67567.3 (18h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 597944
telemt_connections_bad_total 53252
telemt_handshake_timeouts_total 5982
telemt_upstream_connect_attempt_total 13716
telemt_upstream_connect_success_total 13643
telemt_upstream_connect_fail_total 73
telemt_upstream_connect_attempts_per_request{bucket="1"} 13716
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6751
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6872
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 73
telemt_me_keepalive_timeout_total 37
telemt_me_reconnect_attempts_total 15194
telemt_me_reconnect_success_total 10260
telemt_me_reader_eof_total 11056
telemt_me_idle_close_by_peer_total 11056
telemt_me_route_drop_no_conn_total 402092
telemt_me_route_drop_channel_closed_total 34
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 598926
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 838
telemt_desync_full_logged_total 308
telemt_desync_suppressed_total 530
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 322
telemt_desync_frames_bucket_total{bucket="gt_10"} 306
telemt_pool_swap_total 60
telemt_me_writer_removed_unexpected_total 10572
telemt_me_refill_failed_total 152
telemt_me_writer_restored_same_endpoint_total 10246
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 312
telemt_user_connections_total{user="hello"} 507699
telemt_user_connections_current{user="hello"} 900
telemt_user_octets_from_client{user="hello"} 7380429720 (6.87 GB)
telemt_user_octets_to_client{user="hello"} 240758901500 (224.22 GB)
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 15334.2 (4h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11931
telemt_connections_bad_total 58
telemt_handshake_timeouts_total 46
telemt_upstream_connect_attempt_total 8669
telemt_upstream_connect_success_total 8597
telemt_upstream_connect_fail_total 72
telemt_upstream_connect_attempts_per_request{bucket="1"} 8669
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4576
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4014
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 7
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 72
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 13007
telemt_me_reconnect_success_total 7673
telemt_me_reader_eof_total 8036
telemt_me_idle_close_by_peer_total 8036
telemt_me_seq_mismatch_total 9
telemt_me_route_drop_no_conn_total 4156
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11534
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 11
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 7915
telemt_me_refill_failed_total 165
telemt_me_writer_restored_same_endpoint_total 7659
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 242
telemt_user_connections_total{user="hello"} 11635
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 335459145 (319.92 MB)
telemt_user_octets_to_client{user="hello"} 21571706022 (20.09 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 8
```