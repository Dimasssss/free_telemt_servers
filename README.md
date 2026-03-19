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

# Server Metrics 2026-03-19 23:11:11 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 21216.8 (5h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 452908
telemt_connections_bad_total 28593
telemt_connections_current 813
telemt_connections_me_current 813
telemt_handshake_timeouts_total 6879
telemt_upstream_connect_attempt_total 3534
telemt_upstream_connect_success_total 3504
telemt_upstream_connect_fail_total 30
telemt_upstream_connect_attempts_per_request{bucket="1"} 3534
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1699
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1791
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 14
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 30
telemt_me_keepalive_timeout_total 23
telemt_me_reconnect_attempts_total 2446
telemt_me_reconnect_success_total 2428
telemt_me_reader_eof_total 2576
telemt_me_idle_close_by_peer_total 2576
telemt_me_route_drop_no_conn_total 134476
telemt_me_route_drop_channel_closed_total 51
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 358939
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1934
telemt_desync_full_logged_total 676
telemt_desync_suppressed_total 1258
telemt_desync_frames_bucket_total{bucket="1_2"} 403
telemt_desync_frames_bucket_total{bucket="3_10"} 632
telemt_desync_frames_bucket_total{bucket="gt_10"} 899
telemt_pool_swap_total 23
telemt_me_writer_close_signal_drop_total 34
telemt_me_writer_removed_unexpected_total 2479
telemt_me_writer_restored_same_endpoint_total 2415
telemt_me_writer_restored_fallback_total 13
telemt_me_async_recovery_trigger_total 267
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 359212
telemt_user_connections_current{user="hello"} 813
telemt_user_octets_from_client{user="hello"} 19896208380 (18.53 GB)
telemt_user_octets_to_client{user="hello"} 132607203656 (123.50 GB)
telemt_user_unique_ips_current{user="hello"} 294
telemt_user_unique_ips_recent_window{user="hello"} 94
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 37671.5 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2847559
telemt_connections_bad_total 122620
telemt_connections_current 1609
telemt_connections_me_current 1609
telemt_handshake_timeouts_total 58254
telemt_upstream_connect_attempt_total 7550
telemt_upstream_connect_success_total 7430
telemt_upstream_connect_fail_total 120
telemt_upstream_connect_attempts_per_request{bucket="1"} 7550
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4480
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2898
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 52
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 120
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 8556
telemt_me_reconnect_success_total 4321
telemt_me_reader_eof_total 4634
telemt_me_idle_close_by_peer_total 4634
telemt_me_route_drop_no_conn_total 1460872
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2432868
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10698
telemt_desync_full_logged_total 3523
telemt_desync_suppressed_total 7175
telemt_desync_frames_bucket_total{bucket="1_2"} 2006
telemt_desync_frames_bucket_total{bucket="3_10"} 4191
telemt_desync_frames_bucket_total{bucket="gt_10"} 4501
telemt_pool_swap_total 30
telemt_me_writer_close_signal_drop_total 50
telemt_me_writer_removed_unexpected_total 4499
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 4266
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 178
telemt_user_connections_total{user="hello"} 2432697
telemt_user_connections_current{user="hello"} 1609
telemt_user_octets_from_client{user="hello"} 38124197030 (35.51 GB)
telemt_user_octets_to_client{user="hello"} 877485858438 (817.22 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 37649.6 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2768185
telemt_connections_bad_total 463180
telemt_connections_current 1171
telemt_connections_me_current 1171
telemt_handshake_timeouts_total 36440
telemt_upstream_connect_attempt_total 5916
telemt_upstream_connect_success_total 5869
telemt_upstream_connect_fail_total 47
telemt_upstream_connect_attempts_per_request{bucket="1"} 5916
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3003
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2850
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 16
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 47
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 4917
telemt_me_reconnect_success_total 3987
telemt_me_reader_eof_total 4158
telemt_me_idle_close_by_peer_total 4157
telemt_me_route_drop_no_conn_total 1880515
telemt_me_route_drop_channel_closed_total 169
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1928527
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7467
telemt_desync_full_logged_total 2260
telemt_desync_suppressed_total 5207
telemt_desync_frames_bucket_total{bucket="1_2"} 1829
telemt_desync_frames_bucket_total{bucket="3_10"} 2851
telemt_desync_frames_bucket_total{bucket="gt_10"} 2787
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 64
telemt_me_writer_removed_unexpected_total 4021
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 3986
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 34
telemt_user_connections_total{user="hello"} 1924321
telemt_user_connections_current{user="hello"} 1171
telemt_user_octets_from_client{user="hello"} 28967967100 (26.98 GB)
telemt_user_octets_to_client{user="hello"} 727823311564 (677.84 GB)
telemt_user_unique_ips_current{user="hello"} 487
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 37637.5 (10h 27m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2415092
telemt_connections_bad_total 100190
telemt_connections_current 1094
telemt_connections_direct_current 1094
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1521
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 29778
telemt_upstream_connect_attempt_total 48893
telemt_upstream_connect_success_total 44891
telemt_upstream_connect_fail_total 4001
telemt_upstream_connect_attempts_per_request{bucket="1"} 48892
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37896
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6470
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 500
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4001
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 7273
telemt_me_reconnect_success_total 4531
telemt_me_reader_eof_total 4692
telemt_me_idle_close_by_peer_total 4691
telemt_me_route_drop_no_conn_total 1837434
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2039857
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8141
telemt_desync_full_logged_total 2567
telemt_desync_suppressed_total 5574
telemt_desync_frames_bucket_total{bucket="1_2"} 1993
telemt_desync_frames_bucket_total{bucket="3_10"} 2961
telemt_desync_frames_bucket_total{bucket="gt_10"} 3187
telemt_pool_swap_total 23
telemt_me_writer_close_signal_drop_total 403
telemt_me_writer_removed_unexpected_total 5092
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 4527
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 561
telemt_user_connections_total{user="hello"} 2077174
telemt_user_connections_current{user="hello"} 1094
telemt_user_octets_from_client{user="hello"} 33936984863 (31.61 GB)
telemt_user_octets_to_client{user="hello"} 552987379782 (515.01 GB)
telemt_user_msgs_from_client{user="hello"} 176124
telemt_user_msgs_to_client{user="hello"} 1275601
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 157
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 91360.8 (25h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6121787
telemt_connections_bad_total 1036979
telemt_connections_current 1134
telemt_connections_direct_current 1134
telemt_relay_adaptive_promotions_total 23
telemt_relay_adaptive_demotions_total 2846
telemt_relay_adaptive_hard_promotions_total 21
telemt_handshake_timeouts_total 110233
telemt_upstream_connect_attempt_total 106116
telemt_upstream_connect_success_total 74793
telemt_upstream_connect_fail_total 31323
telemt_upstream_connect_attempts_per_request{bucket="1"} 106116
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 62775
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10673
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1345
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 31323
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 77013
telemt_me_reconnect_success_total 11476
telemt_me_reader_eof_total 12238
telemt_me_idle_close_by_peer_total 12227
telemt_me_route_drop_no_conn_total 2763367
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4329828
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
telemt_desync_total 19068
telemt_desync_full_logged_total 5962
telemt_desync_suppressed_total 13106
telemt_desync_frames_bucket_total{bucket="1_2"} 3332
telemt_desync_frames_bucket_total{bucket="3_10"} 7824
telemt_desync_frames_bucket_total{bucket="gt_10"} 7912
telemt_pool_swap_total 77
telemt_me_writer_removed_unexpected_total 11762
telemt_me_refill_failed_total 2043
telemt_me_writer_restored_same_endpoint_total 11451
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 286
telemt_user_connections_total{user="hello"} 4387473
telemt_user_connections_current{user="hello"} 1134
telemt_user_octets_from_client{user="hello"} 67835688670 (63.18 GB)
telemt_user_octets_to_client{user="hello"} 1703452129314 (1.55 TB)
telemt_user_msgs_from_client{user="hello"} 617582
telemt_user_msgs_to_client{user="hello"} 2267782
telemt_user_unique_ips_current{user="hello"} 468
telemt_user_unique_ips_recent_window{user="hello"} 149
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 37600.7 (10h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 654930
telemt_connections_bad_total 56345
telemt_connections_current 323
telemt_connections_me_current 323
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 12801
telemt_upstream_connect_attempt_total 10813
telemt_upstream_connect_success_total 10537
telemt_upstream_connect_fail_total 276
telemt_upstream_connect_attempts_per_request{bucket="1"} 10813
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3990
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5770
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 597
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 276
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 5153
telemt_me_reconnect_success_total 5056
telemt_me_reader_eof_total 5269
telemt_me_idle_close_by_peer_total 5267
telemt_me_route_drop_no_conn_total 453242
telemt_me_route_drop_channel_closed_total 143
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 550041
telemt_me_writer_pick_total{mode="p2c",result="success_fallback"} 881
telemt_me_writer_pick_total{mode="p2c",result="full"} 7065
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_writer_pick_blocking_fallback_total 8012
telemt_me_endpoint_quarantine_total 22
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1380
telemt_desync_full_logged_total 514
telemt_desync_suppressed_total 866
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 566
telemt_desync_frames_bucket_total{bucket="gt_10"} 596
telemt_pool_swap_total 31
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 149
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 5099
telemt_me_writer_restored_same_endpoint_total 5047
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 537333
telemt_user_connections_current{user="hello"} 323
telemt_user_octets_from_client{user="hello"} 7043223632 (6.56 GB)
telemt_user_octets_to_client{user="hello"} 129896188467 (120.98 GB)
telemt_user_msgs_from_client{user="hello"} 9277
telemt_user_msgs_to_client{user="hello"} 14748
telemt_user_unique_ips_current{user="hello"} 139
telemt_user_unique_ips_recent_window{user="hello"} 35
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 37602.1 (10h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1920456
telemt_connections_bad_total 116386
telemt_connections_current 1227
telemt_connections_me_current 1227
telemt_handshake_timeouts_total 35682
telemt_upstream_connect_attempt_total 6419
telemt_upstream_connect_success_total 6371
telemt_upstream_connect_fail_total 48
telemt_upstream_connect_attempts_per_request{bucket="1"} 6419
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3408
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2927
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 36
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 48
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 4518
telemt_me_reconnect_success_total 4481
telemt_me_reader_eof_total 4724
telemt_me_idle_close_by_peer_total 4724
telemt_me_route_drop_no_conn_total 713815
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1657102
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8832
telemt_desync_full_logged_total 2810
telemt_desync_suppressed_total 6022
telemt_desync_frames_bucket_total{bucket="1_2"} 1618
telemt_desync_frames_bucket_total{bucket="3_10"} 3096
telemt_desync_frames_bucket_total{bucket="gt_10"} 4118
telemt_pool_swap_total 36
telemt_me_writer_close_signal_drop_total 36
telemt_me_writer_removed_unexpected_total 4558
telemt_me_writer_restored_same_endpoint_total 4464
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 77
telemt_user_connections_total{user="hello"} 1656239
telemt_user_connections_current{user="hello"} 1227
telemt_user_octets_from_client{user="hello"} 28126834380 (26.20 GB)
telemt_user_octets_to_client{user="hello"} 836836585236 (779.36 GB)
telemt_user_unique_ips_current{user="hello"} 518
telemt_user_unique_ips_recent_window{user="hello"} 93
```