# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt  
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

**Принимаю донаты криптой для добавления и продления серверов:**  
- TON: UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB

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

# Server Metrics 2026-03-20 06:34:57 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 47839.7 (13h 17m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 959012
telemt_connections_bad_total 59417
telemt_connections_current 1572
telemt_connections_me_current 1572
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 25429
telemt_upstream_connect_attempt_total 9274
telemt_upstream_connect_success_total 9168
telemt_upstream_connect_fail_total 106
telemt_upstream_connect_attempts_per_request{bucket="1"} 9274
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5013
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4125
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 106
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5703
telemt_me_reconnect_success_total 5659
telemt_me_reader_eof_total 5994
telemt_me_idle_close_by_peer_total 5993
telemt_me_route_drop_no_conn_total 275313
telemt_me_route_drop_channel_closed_total 97
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 780228
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 4091
telemt_desync_full_logged_total 1480
telemt_desync_suppressed_total 2611
telemt_desync_frames_bucket_total{bucket="1_2"} 802
telemt_desync_frames_bucket_total{bucket="3_10"} 1591
telemt_desync_frames_bucket_total{bucket="gt_10"} 1698
telemt_pool_swap_total 52
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 5720
telemt_me_writer_restored_same_endpoint_total 5646
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 779610
telemt_user_connections_current{user="hello"} 1572
telemt_user_octets_from_client{user="hello"} 34026714616 (31.69 GB)
telemt_user_octets_to_client{user="hello"} 269413718525 (250.91 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 586
telemt_user_unique_ips_recent_window{user="hello"} 239
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 64295.4 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 4228199
telemt_connections_bad_total 394050
telemt_connections_current 5549
telemt_connections_me_current 5549
telemt_handshake_timeouts_total 97742
telemt_upstream_connect_attempt_total 12101
telemt_upstream_connect_success_total 11877
telemt_upstream_connect_fail_total 224
telemt_upstream_connect_attempts_per_request{bucket="1"} 12101
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6685
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5129
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 63
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 224
telemt_me_keepalive_timeout_total 56
telemt_me_reconnect_attempts_total 11708
telemt_me_reconnect_success_total 7452
telemt_me_reader_eof_total 7971
telemt_me_idle_close_by_peer_total 7970
telemt_me_route_drop_no_conn_total 1961667
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3454009
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 13755
telemt_desync_full_logged_total 4567
telemt_desync_suppressed_total 9188
telemt_desync_frames_bucket_total{bucket="1_2"} 2698
telemt_desync_frames_bucket_total{bucket="3_10"} 5353
telemt_desync_frames_bucket_total{bucket="gt_10"} 5704
telemt_pool_swap_total 57
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 67
telemt_me_writer_removed_unexpected_total 7681
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 7397
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 229
telemt_user_connections_total{user="hello"} 3453657
telemt_user_connections_current{user="hello"} 5549
telemt_user_octets_from_client{user="hello"} 50503105346 (47.03 GB)
telemt_user_octets_to_client{user="hello"} 1289187452134 (1.17 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1739
telemt_user_unique_ips_recent_window{user="hello"} 785
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 64275.6 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3894348
telemt_connections_bad_total 509740
telemt_connections_current 4526
telemt_connections_me_current 4526
telemt_handshake_timeouts_total 61456
telemt_upstream_connect_attempt_total 11862
telemt_upstream_connect_success_total 11767
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 11862
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6096
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5454
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 11
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 206
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 1570
telemt_me_reconnect_attempts_total 8058
telemt_me_reconnect_success_total 7101
telemt_me_reader_eof_total 7444
telemt_me_idle_close_by_peer_total 7440
telemt_me_route_drop_no_conn_total 2429753
telemt_me_route_drop_channel_closed_total 233
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2784156
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 179
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9555
telemt_desync_full_logged_total 3002
telemt_desync_suppressed_total 6553
telemt_desync_frames_bucket_total{bucket="1_2"} 2396
telemt_desync_frames_bucket_total{bucket="3_10"} 3653
telemt_desync_frames_bucket_total{bucket="gt_10"} 3506
telemt_pool_swap_total 64
telemt_me_writer_close_signal_drop_total 272
telemt_me_writer_removed_unexpected_total 7186
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 7100
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 85
telemt_user_connections_total{user="hello"} 2790577
telemt_user_connections_current{user="hello"} 4526
telemt_user_octets_from_client{user="hello"} 39434468098 (36.73 GB)
telemt_user_octets_to_client{user="hello"} 1058647537056 (985.94 GB)
telemt_user_msgs_from_client{user="hello"} 2664
telemt_user_msgs_to_client{user="hello"} 1842
telemt_user_unique_ips_current{user="hello"} 1114
telemt_user_unique_ips_recent_window{user="hello"} 988
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 64261.1 (17h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3846924
telemt_connections_bad_total 267395
telemt_connections_current 4567
telemt_connections_me_current 4567
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 55947
telemt_upstream_connect_attempt_total 67726
telemt_upstream_connect_success_total 62996
telemt_upstream_connect_fail_total 4730
telemt_upstream_connect_attempts_per_request{bucket="1"} 67726
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 52538
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9721
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 712
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4730
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 10377
telemt_me_reconnect_success_total 7395
telemt_me_reader_eof_total 7722
telemt_me_idle_close_by_peer_total 7721
telemt_me_route_drop_no_conn_total 3519757
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3169327
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11252
telemt_desync_full_logged_total 3426
telemt_desync_suppressed_total 7826
telemt_desync_frames_bucket_total{bucket="1_2"} 2627
telemt_desync_frames_bucket_total{bucket="3_10"} 4304
telemt_desync_frames_bucket_total{bucket="gt_10"} 4321
telemt_pool_swap_total 52
telemt_me_writer_close_signal_drop_total 676
telemt_me_writer_removed_unexpected_total 8118
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 7391
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 410
telemt_me_writer_removed_unexpected_minus_restored_total 723
telemt_user_connections_total{user="hello"} 3220195
telemt_user_connections_current{user="hello"} 4567
telemt_user_octets_from_client{user="hello"} 43795643600 (40.79 GB)
telemt_user_octets_to_client{user="hello"} 824523052251 (767.90 GB)
telemt_user_msgs_from_client{user="hello"} 260491
telemt_user_msgs_to_client{user="hello"} 1782062
telemt_user_unique_ips_current{user="hello"} 1332
telemt_user_unique_ips_recent_window{user="hello"} 792
```

## rdp-onedash.ru

```
telemt 3.3.24

telemt_uptime_seconds 1844.7 (0h 30m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 217041
telemt_connections_bad_total 27095
telemt_connections_current 4411
telemt_connections_me_current 4411
telemt_handshake_timeouts_total 4031
telemt_upstream_connect_attempt_total 323
telemt_upstream_connect_success_total 321
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 181
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 140
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 197
telemt_me_reconnect_success_total 195
telemt_me_reader_eof_total 162
telemt_me_idle_close_by_peer_total 162
telemt_me_route_drop_no_conn_total 129893
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 168920
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 15
telemt_me_endpoint_quarantine_total 16
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 488
telemt_desync_full_logged_total 171
telemt_desync_suppressed_total 317
telemt_desync_frames_bucket_total{bucket="1_2"} 82
telemt_desync_frames_bucket_total{bucket="3_10"} 211
telemt_desync_frames_bucket_total{bucket="gt_10"} 195
telemt_me_writer_close_signal_drop_total 22
telemt_me_writer_removed_unexpected_total 184
telemt_me_writer_restored_same_endpoint_total 165
telemt_me_writer_restored_fallback_total 30
telemt_me_async_recovery_trigger_total 156
telemt_user_connections_total{user="hello"} 168783
telemt_user_connections_current{user="hello"} 4411
telemt_user_octets_from_client{user="hello"} 2613605964 (2.43 GB)
telemt_user_octets_to_client{user="hello"} 48828244500 (45.47 GB)
telemt_user_unique_ips_current{user="hello"} 1435
telemt_user_unique_ips_recent_window{user="hello"} 607
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 1779.3 (0h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 26563
telemt_connections_bad_total 3701
telemt_connections_current 542
telemt_connections_me_current 542
telemt_handshake_timeouts_total 388
telemt_upstream_connect_attempt_total 239
telemt_upstream_connect_success_total 238
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 239
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 127
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 110
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 127
telemt_me_reconnect_success_total 125
telemt_me_reader_eof_total 104
telemt_me_idle_close_by_peer_total 104
telemt_me_route_drop_no_conn_total 15668
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 28133
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 117
telemt_desync_full_logged_total 33
telemt_desync_suppressed_total 84
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 50
telemt_desync_frames_bucket_total{bucket="gt_10"} 49
telemt_pool_swap_total 1
telemt_me_writer_close_signal_drop_total 23
telemt_me_writer_removed_unexpected_total 126
telemt_me_writer_restored_same_endpoint_total 117
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 198
telemt_me_writer_removed_unexpected_minus_restored_total 1
telemt_user_connections_total{user="hello"} 21256
telemt_user_connections_current{user="hello"} 542
telemt_user_octets_from_client{user="hello"} 189213268 (180.45 MB)
telemt_user_octets_to_client{user="hello"} 7861964032 (7.32 GB)
telemt_user_unique_ips_current{user="hello"} 210
telemt_user_unique_ips_recent_window{user="hello"} 87
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 64225.6 (17h 50m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2742676
telemt_connections_bad_total 178694
telemt_connections_current 4195
telemt_connections_me_current 4195
telemt_handshake_timeouts_total 48280
telemt_upstream_connect_attempt_total 11417
telemt_upstream_connect_success_total 11346
telemt_upstream_connect_fail_total 71
telemt_upstream_connect_attempts_per_request{bucket="1"} 11417
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6135
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5174
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 71
telemt_me_keepalive_timeout_total 14
telemt_me_reconnect_attempts_total 8199
telemt_me_reconnect_success_total 8147
telemt_me_reader_eof_total 8614
telemt_me_idle_close_by_peer_total 8614
telemt_me_route_drop_no_conn_total 939724
telemt_me_route_drop_channel_closed_total 7
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2294061
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11490
telemt_desync_full_logged_total 3761
telemt_desync_suppressed_total 7729
telemt_desync_frames_bucket_total{bucket="1_2"} 2286
telemt_desync_frames_bucket_total{bucket="3_10"} 4045
telemt_desync_frames_bucket_total{bucket="gt_10"} 5159
telemt_pool_swap_total 66
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 8258
telemt_me_writer_restored_same_endpoint_total 8130
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 2292917
telemt_user_connections_current{user="hello"} 4195
telemt_user_octets_from_client{user="hello"} 50100652372 (46.66 GB)
telemt_user_octets_to_client{user="hello"} 1204201735000 (1.10 TB)
telemt_user_unique_ips_current{user="hello"} 1323
telemt_user_unique_ips_recent_window{user="hello"} 522
```