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

# Server Metrics 2026-03-17 11:20:17 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.19

telemt_uptime_seconds 59701.1 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 527901
telemt_connections_bad_total 4475
telemt_handshake_timeouts_total 15960
telemt_upstream_connect_attempt_total 14772
telemt_upstream_connect_success_total 14331
telemt_upstream_connect_fail_total 441
telemt_upstream_connect_attempts_per_request{bucket="1"} 14772
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7586
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6595
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 150
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 441
telemt_me_keepalive_timeout_total 110
telemt_me_reconnect_attempts_total 10584
telemt_me_reconnect_success_total 9050
telemt_me_reader_eof_total 9624
telemt_me_idle_close_by_peer_total 9623
telemt_me_route_drop_no_conn_total 173314
telemt_me_route_drop_channel_closed_total 47
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 477565
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3805
telemt_desync_full_logged_total 998
telemt_desync_suppressed_total 2807
telemt_desync_frames_bucket_total{bucket="1_2"} 1092
telemt_desync_frames_bucket_total{bucket="3_10"} 1593
telemt_desync_frames_bucket_total{bucket="gt_10"} 1120
telemt_pool_swap_total 56
telemt_me_writer_removed_unexpected_total 9233
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 9028
telemt_me_writer_restored_fallback_total 22
telemt_me_async_recovery_trigger_total 46
telemt_me_writer_removed_unexpected_minus_restored_total 183
telemt_user_connections_total{user="hello"} 479504
telemt_user_connections_current{user="hello"} 930
telemt_user_octets_from_client{user="hello"} 6582395867 (6.13 GB)
telemt_user_octets_to_client{user="hello"} 176644790683 (164.51 GB)
telemt_user_msgs_from_client{user="hello"} 17216
telemt_user_msgs_to_client{user="hello"} 23688
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## psb.hosting

```
telemt 3.3.19

telemt_uptime_seconds 59952.8 (16h 39m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 294935
telemt_connections_bad_total 10448
telemt_handshake_timeouts_total 17319
telemt_upstream_connect_attempt_total 15224
telemt_upstream_connect_success_total 15006
telemt_upstream_connect_fail_total 218
telemt_upstream_connect_attempts_per_request{bucket="1"} 15224
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6475
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8330
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 201
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 218
telemt_me_keepalive_timeout_total 13
telemt_me_reconnect_attempts_total 24363
telemt_me_reconnect_success_total 12030
telemt_me_reader_eof_total 12994
telemt_me_idle_close_by_peer_total 12994
telemt_me_route_drop_no_conn_total 110442
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 252712
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 5
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 743
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 473
telemt_desync_frames_bucket_total{bucket="1_2"} 210
telemt_desync_frames_bucket_total{bucket="3_10"} 322
telemt_desync_frames_bucket_total{bucket="gt_10"} 211
telemt_pool_swap_total 37
telemt_me_writer_removed_unexpected_total 12546
telemt_me_refill_failed_total 384
telemt_me_writer_restored_same_endpoint_total 12014
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 1056
telemt_me_writer_removed_unexpected_minus_restored_total 516
telemt_user_connections_total{user="hello"} 252700
telemt_user_connections_current{user="hello"} 583
telemt_user_octets_from_client{user="hello"} 3004662592 (2.80 GB)
telemt_user_octets_to_client{user="hello"} 91698327208 (85.40 GB)
telemt_user_unique_ips_current{user="hello"} 182
telemt_user_unique_ips_recent_window{user="hello"} 68
```

## koara.io

```
telemt 3.3.19

telemt_uptime_seconds 59729.2 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 173934
telemt_connections_bad_total 7640
telemt_handshake_timeouts_total 13853
telemt_upstream_connect_attempt_total 15739
telemt_upstream_connect_success_total 15657
telemt_upstream_connect_fail_total 82
telemt_upstream_connect_attempts_per_request{bucket="1"} 15739
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6918
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8671
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 82
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 14509
telemt_me_reconnect_success_total 12639
telemt_me_reader_eof_total 13510
telemt_me_idle_close_by_peer_total 13510
telemt_me_route_drop_no_conn_total 51512
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 142267
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 520
telemt_desync_full_logged_total 135
telemt_desync_suppressed_total 385
telemt_desync_frames_bucket_total{bucket="1_2"} 224
telemt_desync_frames_bucket_total{bucket="3_10"} 220
telemt_desync_frames_bucket_total{bucket="gt_10"} 76
telemt_pool_swap_total 52
telemt_me_writer_removed_unexpected_total 12866
telemt_me_refill_failed_total 56
telemt_me_writer_restored_same_endpoint_total 12628
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 227
telemt_user_connections_total{user="hello"} 142171
telemt_user_connections_current{user="hello"} 308
telemt_user_octets_from_client{user="hello"} 13290023500 (12.38 GB)
telemt_user_octets_to_client{user="hello"} 41510225760 (38.66 GB)
telemt_user_unique_ips_current{user="hello"} 118
telemt_user_unique_ips_recent_window{user="hello"} 39
```

## landvps.ru

```
telemt 3.3.19

telemt_uptime_seconds 59787.9 (16h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 392151
telemt_connections_bad_total 6692
telemt_handshake_timeouts_total 11975
telemt_upstream_connect_attempt_total 13611
telemt_upstream_connect_success_total 13483
telemt_upstream_connect_fail_total 128
telemt_upstream_connect_attempts_per_request{bucket="1"} 13611
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6353
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7045
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 77
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 128
telemt_me_keepalive_timeout_total 9
telemt_me_reconnect_attempts_total 11529
telemt_me_reconnect_success_total 10424
telemt_me_reader_eof_total 11078
telemt_me_idle_close_by_peer_total 11078
telemt_me_route_drop_no_conn_total 110056
telemt_me_route_drop_channel_closed_total 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324669
telemt_me_writer_pick_total{mode="p2c",result="full"} 11
telemt_me_writer_pick_total{mode="p2c",result="closed"} 23
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 927
telemt_desync_full_logged_total 335
telemt_desync_suppressed_total 592
telemt_desync_frames_bucket_total{bucket="1_2"} 222
telemt_desync_frames_bucket_total{bucket="3_10"} 397
telemt_desync_frames_bucket_total{bucket="gt_10"} 308
telemt_pool_swap_total 49
telemt_me_writer_removed_unexpected_total 10629
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 10416
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 324609
telemt_user_connections_current{user="hello"} 743
telemt_user_octets_from_client{user="hello"} 4248008050 (3.96 GB)
telemt_user_octets_to_client{user="hello"} 119632064469 (111.42 GB)
telemt_user_msgs_from_client{user="hello"} 65
telemt_user_msgs_to_client{user="hello"} 189
telemt_user_unique_ips_current{user="hello"} 200
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## rdp-onedash.ru

```
telemt 3.3.19

telemt_uptime_seconds 59759.9 (16h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 207776
telemt_connections_bad_total 51854
telemt_handshake_timeouts_total 3005
telemt_upstream_connect_attempt_total 17755
telemt_upstream_connect_success_total 17522
telemt_upstream_connect_fail_total 233
telemt_upstream_connect_attempts_per_request{bucket="1"} 17755
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7853
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9458
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 211
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 233
telemt_me_keepalive_timeout_total 2
telemt_me_reconnect_attempts_total 28056
telemt_me_reconnect_success_total 14404
telemt_me_reader_eof_total 15429
telemt_me_idle_close_by_peer_total 15429
telemt_me_route_drop_no_conn_total 54814
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 146237
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 857
telemt_desync_full_logged_total 164
telemt_desync_suppressed_total 693
telemt_desync_frames_bucket_total{bucket="1_2"} 452
telemt_desync_frames_bucket_total{bucket="3_10"} 312
telemt_desync_frames_bucket_total{bucket="gt_10"} 93
telemt_pool_swap_total 34
telemt_me_writer_removed_unexpected_total 15008
telemt_me_refill_failed_total 424
telemt_me_writer_restored_same_endpoint_total 14396
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 143
telemt_me_writer_removed_unexpected_minus_restored_total 604
telemt_user_connections_total{user="hello"} 146256
telemt_user_connections_current{user="hello"} 300
telemt_user_octets_from_client{user="hello"} 2065734267 (1.92 GB)
telemt_user_octets_to_client{user="hello"} 62997728874 (58.67 GB)
telemt_user_msgs_from_client{user="hello"} 265
telemt_user_msgs_to_client{user="hello"} 707
telemt_user_unique_ips_current{user="hello"} 103
telemt_user_unique_ips_recent_window{user="hello"} 44
```

## hostvds.com

```
telemt 3.3.19

telemt_uptime_seconds 59921.6 (16h 38m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 487900
telemt_connections_bad_total 51641
telemt_handshake_timeouts_total 4684
telemt_upstream_connect_attempt_total 12179
telemt_upstream_connect_success_total 12113
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 12179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 19
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 31
telemt_me_reconnect_attempts_total 13016
telemt_me_reconnect_success_total 9124
telemt_me_reader_eof_total 9837
telemt_me_idle_close_by_peer_total 9837
telemt_me_route_drop_no_conn_total 330155
telemt_me_route_drop_channel_closed_total 17
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 482583
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 24
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 719
telemt_desync_full_logged_total 270
telemt_desync_suppressed_total 449
telemt_desync_frames_bucket_total{bucket="1_2"} 193
telemt_desync_frames_bucket_total{bucket="3_10"} 278
telemt_desync_frames_bucket_total{bucket="gt_10"} 248
telemt_pool_swap_total 55
telemt_me_writer_removed_unexpected_total 9386
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 9110
telemt_me_writer_restored_fallback_total 14
telemt_me_async_recovery_trigger_total 270
telemt_me_writer_removed_unexpected_minus_restored_total 262
telemt_user_connections_total{user="hello"} 404280
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 5946013464 (5.54 GB)
telemt_user_octets_to_client{user="hello"} 205218947504 (191.13 GB)
telemt_user_unique_ips_current{user="hello"} 290
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## 4vps.su

```
telemt 3.3.19

telemt_uptime_seconds 7688.1 (2h 8m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5635
telemt_connections_bad_total 34
telemt_handshake_timeouts_total 34
telemt_upstream_connect_attempt_total 4148
telemt_upstream_connect_success_total 4107
telemt_upstream_connect_fail_total 41
telemt_upstream_connect_attempts_per_request{bucket="1"} 4148
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2172
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1935
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 41
telemt_me_keepalive_timeout_total 12
telemt_me_reconnect_attempts_total 4455
telemt_me_reconnect_success_total 3555
telemt_me_reader_eof_total 3677
telemt_me_idle_close_by_peer_total 3677
telemt_me_seq_mismatch_total 5
telemt_me_route_drop_no_conn_total 2251
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5329
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 7
telemt_me_endpoint_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 3
telemt_me_writer_removed_unexpected_total 3619
telemt_me_refill_failed_total 27
telemt_me_writer_restored_same_endpoint_total 3546
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 880
telemt_me_writer_removed_unexpected_minus_restored_total 64
telemt_user_connections_total{user="hello"} 5436
telemt_user_connections_current{user="hello"} 77
telemt_user_octets_from_client{user="hello"} 142158041 (135.57 MB)
telemt_user_octets_to_client{user="hello"} 18670348106 (17.39 GB)
telemt_user_msgs_from_client{user="hello"} 350
telemt_user_msgs_to_client{user="hello"} 2305
telemt_user_unique_ips_current{user="hello"} 21
telemt_user_unique_ips_recent_window{user="hello"} 6
```