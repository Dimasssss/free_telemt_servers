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

# Server Metrics 2026-03-17 12:21:25 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 63369.5 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592795
telemt_connections_bad_total 4796
telemt_handshake_timeouts_total 19307
telemt_upstream_connect_attempt_total 15731
telemt_upstream_connect_success_total 15284
telemt_upstream_connect_fail_total 447
telemt_upstream_connect_attempts_per_request{bucket="1"} 15731
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8048
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7086
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 447
telemt_me_keepalive_timeout_total 111
telemt_me_reconnect_attempts_total 12576
telemt_me_reconnect_success_total 9822
telemt_me_reader_eof_total 10454
telemt_me_idle_close_by_peer_total 10453
telemt_me_route_drop_no_conn_total 192268
telemt_me_route_drop_channel_closed_total 56
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 533998
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4061
telemt_desync_full_logged_total 1083
telemt_desync_suppressed_total 2978
telemt_desync_frames_bucket_total{bucket="1_2"} 1177
telemt_desync_frames_bucket_total{bucket="3_10"} 1692
telemt_desync_frames_bucket_total{bucket="gt_10"} 1192
telemt_pool_swap_total 57
telemt_me_writer_removed_unexpected_total 10048
telemt_me_refill_failed_total 81
telemt_me_writer_restored_same_endpoint_total 9800
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 226
telemt_user_connections_total{user="hello"} 535903
telemt_user_connections_current{user="hello"} 901
telemt_user_octets_from_client{user="hello"} 7255134359 (6.76 GB)
telemt_user_octets_to_client{user="hello"} 194010942027 (180.69 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 142
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 63621.8 (17h 40m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 338682
telemt_connections_bad_total 17143
telemt_handshake_timeouts_total 19217
telemt_upstream_connect_attempt_total 16089
telemt_upstream_connect_success_total 15866
telemt_upstream_connect_fail_total 223
telemt_upstream_connect_attempts_per_request{bucket="1"} 16089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6809
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8792
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 265
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 223
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 25050
telemt_me_reconnect_success_total 12714
telemt_me_reader_eof_total 13713
telemt_me_idle_close_by_peer_total 13713
telemt_me_route_drop_no_conn_total 123632
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 284414
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1004
telemt_desync_full_logged_total 344
telemt_desync_suppressed_total 660
telemt_desync_frames_bucket_total{bucket="1_2"} 249
telemt_desync_frames_bucket_total{bucket="3_10"} 424
telemt_desync_frames_bucket_total{bucket="gt_10"} 331
telemt_pool_swap_total 39
telemt_me_writer_removed_unexpected_total 13240
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12698
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 526
telemt_user_connections_total{user="hello"} 284397
telemt_user_connections_current{user="hello"} 647
telemt_user_octets_from_client{user="hello"} 3266466328 (3.04 GB)
telemt_user_octets_to_client{user="hello"} 103717601188 (96.59 GB)
telemt_user_unique_ips_current{user="hello"} 172
telemt_user_unique_ips_recent_window{user="hello"} 84
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 63397.1 (17h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 194045
telemt_connections_bad_total 7725
telemt_handshake_timeouts_total 16275
telemt_upstream_connect_attempt_total 16601
telemt_upstream_connect_success_total 16514
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 16601
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7322
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9117
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 5
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 70
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 15189
telemt_me_reconnect_success_total 13315
telemt_me_reader_eof_total 14226
telemt_me_idle_close_by_peer_total 14226
telemt_me_route_drop_no_conn_total 58000
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 159351
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 603
telemt_desync_full_logged_total 159
telemt_desync_suppressed_total 444
telemt_desync_frames_bucket_total{bucket="1_2"} 243
telemt_desync_frames_bucket_total{bucket="3_10"} 258
telemt_desync_frames_bucket_total{bucket="gt_10"} 102
telemt_pool_swap_total 54
telemt_me_writer_removed_unexpected_total 13564
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 13304
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 249
telemt_user_connections_total{user="hello"} 159247
telemt_user_connections_current{user="hello"} 332
telemt_user_octets_from_client{user="hello"} 14968578172 (13.94 GB)
telemt_user_octets_to_client{user="hello"} 44810629288 (41.73 GB)
telemt_user_unique_ips_current{user="hello"} 111
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 63456.4 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 443383
telemt_connections_bad_total 7486
telemt_handshake_timeouts_total 12327
telemt_upstream_connect_attempt_total 15370
telemt_upstream_connect_success_total 15233
telemt_upstream_connect_fail_total 136
telemt_upstream_connect_attempts_per_request{bucket="1"} 15369
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7564
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7568
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 92
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 136
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 14403
telemt_me_reconnect_success_total 11031
telemt_me_reader_eof_total 11781
telemt_me_idle_close_by_peer_total 11781
telemt_me_route_drop_no_conn_total 125319
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 370996
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1211
telemt_desync_full_logged_total 434
telemt_desync_suppressed_total 777
telemt_desync_frames_bucket_total{bucket="1_2"} 296
telemt_desync_frames_bucket_total{bucket="3_10"} 532
telemt_desync_frames_bucket_total{bucket="gt_10"} 383
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 11318
telemt_me_refill_failed_total 101
telemt_me_writer_restored_same_endpoint_total 11022
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 287
telemt_user_connections_total{user="hello"} 371874
telemt_user_connections_current{user="hello"} 744
telemt_user_octets_from_client{user="hello"} 4926046042 (4.59 GB)
telemt_user_octets_to_client{user="hello"} 132504455399 (123.40 GB)
telemt_user_msgs_from_client{user="hello"} 4070
telemt_user_msgs_to_client{user="hello"} 5224
telemt_user_unique_ips_current{user="hello"} 193
telemt_user_unique_ips_recent_window{user="hello"} 91
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 63428.4 (17h 37m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 226332
telemt_connections_bad_total 52520
telemt_handshake_timeouts_total 3108
telemt_upstream_connect_attempt_total 18583
telemt_upstream_connect_success_total 18341
telemt_upstream_connect_fail_total 242
telemt_upstream_connect_attempts_per_request{bucket="1"} 18583
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8221
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9883
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 237
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 242
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28703
telemt_me_reconnect_success_total 15043
telemt_me_reader_eof_total 16095
telemt_me_idle_close_by_peer_total 16095
telemt_me_route_drop_no_conn_total 59751
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 163054
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 950
telemt_desync_full_logged_total 190
telemt_desync_suppressed_total 760
telemt_desync_frames_bucket_total{bucket="1_2"} 496
telemt_desync_frames_bucket_total{bucket="3_10"} 349
telemt_desync_frames_bucket_total{bucket="gt_10"} 105
telemt_pool_swap_total 36
telemt_me_writer_removed_unexpected_total 15660
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 15035
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 617
telemt_user_connections_total{user="hello"} 163067
telemt_user_connections_current{user="hello"} 274
telemt_user_octets_from_client{user="hello"} 2192700163 (2.04 GB)
telemt_user_octets_to_client{user="hello"} 66655356846 (62.08 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 104
telemt_user_unique_ips_recent_window{user="hello"} 49
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 63589.8 (17h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 537102
telemt_connections_bad_total 52072
telemt_handshake_timeouts_total 4974
telemt_upstream_connect_attempt_total 12801
telemt_upstream_connect_success_total 12732
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 12801
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6301
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6411
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_keepalive_timeout_total 32
telemt_me_reconnect_attempts_total 13459
telemt_me_reconnect_success_total 9564
telemt_me_reader_eof_total 10312
telemt_me_idle_close_by_peer_total 10312
telemt_me_route_drop_no_conn_total 350401
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 529168
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 807
telemt_desync_full_logged_total 296
telemt_desync_suppressed_total 511
telemt_desync_frames_bucket_total{bucket="1_2"} 207
telemt_desync_frames_bucket_total{bucket="3_10"} 310
telemt_desync_frames_bucket_total{bucket="gt_10"} 290
telemt_pool_swap_total 59
telemt_me_writer_removed_unexpected_total 9833
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9550
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 269
telemt_user_connections_total{user="hello"} 450856
telemt_user_connections_current{user="hello"} 992
telemt_user_octets_from_client{user="hello"} 6736261196 (6.27 GB)
telemt_user_octets_to_client{user="hello"} 218970871704 (203.93 GB)
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 140
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 11356.4 (3h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8837
telemt_connections_bad_total 55
telemt_handshake_timeouts_total 38
telemt_upstream_connect_attempt_total 6244
telemt_upstream_connect_success_total 6187
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 6244
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3332
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2855
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 8696
telemt_me_reconnect_success_total 5453
telemt_me_reader_eof_total 5733
telemt_me_idle_close_by_peer_total 5733
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 3305
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8473
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 7
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 5
telemt_me_writer_removed_unexpected_total 5605
telemt_me_refill_failed_total 100
telemt_me_writer_restored_same_endpoint_total 5444
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 152
telemt_user_connections_total{user="hello"} 8578
telemt_user_connections_current{user="hello"} 66
telemt_user_octets_from_client{user="hello"} 188153193 (179.44 MB)
telemt_user_octets_to_client{user="hello"} 19711362714 (18.36 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 19
telemt_user_unique_ips_recent_window{user="hello"} 3
```