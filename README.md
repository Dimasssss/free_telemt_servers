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

# Server Metrics 2026-03-20 02:40:27 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 33772.6 (9h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 627598
telemt_connections_bad_total 40299
telemt_connections_current 749
telemt_connections_me_current 749
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 11753
telemt_upstream_connect_attempt_total 6967
telemt_upstream_connect_success_total 6879
telemt_upstream_connect_fail_total 87
telemt_upstream_connect_attempts_per_request{bucket="1"} 6966
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3902
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2949
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 87
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4110
telemt_me_reconnect_success_total 4070
telemt_me_reader_eof_total 4303
telemt_me_idle_close_by_peer_total 4302
telemt_me_route_drop_no_conn_total 177869
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 499121
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2363
telemt_desync_full_logged_total 854
telemt_desync_suppressed_total 1509
telemt_desync_frames_bucket_total{bucket="1_2"} 485
telemt_desync_frames_bucket_total{bucket="3_10"} 839
telemt_desync_frames_bucket_total{bucket="gt_10"} 1039
telemt_pool_swap_total 37
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 4106
telemt_me_writer_restored_same_endpoint_total 4057
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 500554
telemt_user_connections_current{user="hello"} 749
telemt_user_octets_from_client{user="hello"} 30418096440 (28.33 GB)
telemt_user_octets_to_client{user="hello"} 174520392705 (162.53 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 101
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 50228.2 (13h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3096271
telemt_connections_bad_total 145657
telemt_connections_current 1669
telemt_connections_me_current 1669
telemt_handshake_timeouts_total 68121
telemt_upstream_connect_attempt_total 9888
telemt_upstream_connect_success_total 9719
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 9888
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5574
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4087
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10244
telemt_me_reconnect_success_total 5998
telemt_me_reader_eof_total 6418
telemt_me_idle_close_by_peer_total 6418
telemt_me_route_drop_no_conn_total 1524270
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2643231
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11311
telemt_desync_full_logged_total 3736
telemt_desync_suppressed_total 7575
telemt_desync_frames_bucket_total{bucket="1_2"} 2159
telemt_desync_frames_bucket_total{bucket="3_10"} 4421
telemt_desync_frames_bucket_total{bucket="gt_10"} 4731
telemt_pool_swap_total 43
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 53
telemt_me_writer_removed_unexpected_total 6200
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5943
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 202
telemt_user_connections_total{user="hello"} 2642988
telemt_user_connections_current{user="hello"} 1669
telemt_user_octets_from_client{user="hello"} 40243176570 (37.48 GB)
telemt_user_octets_to_client{user="hello"} 982084256354 (914.64 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 710
telemt_user_unique_ips_recent_window{user="hello"} 192
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 50206.3 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3016534
telemt_connections_bad_total 478155
telemt_connections_current 1305
telemt_connections_me_current 1305
telemt_handshake_timeouts_total 46649
telemt_upstream_connect_attempt_total 8179
telemt_upstream_connect_success_total 8121
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 8179
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4118
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3986
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6563
telemt_me_reconnect_success_total 5628
telemt_me_reader_eof_total 5911
telemt_me_idle_close_by_peer_total 5910
telemt_me_route_drop_no_conn_total 1937599
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2082646
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7834
telemt_desync_full_logged_total 2389
telemt_desync_suppressed_total 5445
telemt_desync_frames_bucket_total{bucket="1_2"} 1914
telemt_desync_frames_bucket_total{bucket="3_10"} 2972
telemt_desync_frames_bucket_total{bucket="gt_10"} 2948
telemt_pool_swap_total 49
telemt_me_writer_close_signal_drop_total 70
telemt_me_writer_removed_unexpected_total 5682
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5627
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 54
telemt_user_connections_total{user="hello"} 2078269
telemt_user_connections_current{user="hello"} 1305
telemt_user_octets_from_client{user="hello"} 30502956932 (28.41 GB)
telemt_user_octets_to_client{user="hello"} 800318303720 (745.35 GB)
telemt_user_unique_ips_current{user="hello"} 534
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 50194.0 (13h 56m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2681062
telemt_connections_bad_total 188034
telemt_connections_current 1209
telemt_connections_me_current 1209
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31877
telemt_upstream_connect_attempt_total 56038
telemt_upstream_connect_success_total 51739
telemt_upstream_connect_fail_total 4299
telemt_upstream_connect_attempts_per_request{bucket="1"} 56038
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43425
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7757
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 532
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4299
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8851
telemt_me_reconnect_success_total 5998
telemt_me_reader_eof_total 6244
telemt_me_idle_close_by_peer_total 6243
telemt_me_route_drop_no_conn_total 1878550
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2186523
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8432
telemt_desync_full_logged_total 2677
telemt_desync_suppressed_total 5755
telemt_desync_frames_bucket_total{bucket="1_2"} 2073
telemt_desync_frames_bucket_total{bucket="3_10"} 3070
telemt_desync_frames_bucket_total{bucket="gt_10"} 3289
telemt_pool_swap_total 36
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6634
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5994
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 636
telemt_user_connections_total{user="hello"} 2228599
telemt_user_connections_current{user="hello"} 1209
telemt_user_octets_from_client{user="hello"} 36147461929 (33.66 GB)
telemt_user_octets_to_client{user="hello"} 630591050845 (587.28 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 477
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 103917.1 (28h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6343196
telemt_connections_bad_total 1052071
telemt_connections_current 1414
telemt_connections_me_current 1414
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 114653
telemt_upstream_connect_attempt_total 128169
telemt_upstream_connect_success_total 94881
telemt_upstream_connect_fail_total 33288
telemt_upstream_connect_attempts_per_request{bucket="1"} 128169
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80649
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12796
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1436
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33288
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79053
telemt_me_reconnect_success_total 13381
telemt_me_reader_eof_total 14407
telemt_me_idle_close_by_peer_total 14393
telemt_me_route_drop_no_conn_total 2815174
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4504652
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
telemt_desync_total 19690
telemt_desync_full_logged_total 6247
telemt_desync_suppressed_total 13443
telemt_desync_frames_bucket_total{bucket="1_2"} 3470
telemt_desync_frames_bucket_total{bucket="3_10"} 8120
telemt_desync_frames_bucket_total{bucket="gt_10"} 8100
telemt_pool_swap_total 91
telemt_me_writer_removed_unexpected_total 13690
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13356
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 4579872
telemt_user_connections_current{user="hello"} 1414
telemt_user_octets_from_client{user="hello"} 73051821404 (68.03 GB)
telemt_user_octets_to_client{user="hello"} 1762986536056 (1.60 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 584
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 50157.2 (13h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 850182
telemt_connections_bad_total 80354
telemt_connections_current 510
telemt_connections_me_current 510
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13139
telemt_upstream_connect_attempt_total 13769
telemt_upstream_connect_success_total 13439
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13769
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5579
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7019
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 58
telemt_me_keepalive_timeout_total 546
telemt_me_reconnect_attempts_total 6736
telemt_me_reconnect_success_total 6627
telemt_me_reader_eof_total 7008
telemt_me_idle_close_by_peer_total 7005
telemt_me_route_drop_no_conn_total 472376
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585597
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
telemt_desync_total 1401
telemt_desync_full_logged_total 526
telemt_desync_suppressed_total 875
telemt_desync_frames_bucket_total{bucket="1_2"} 219
telemt_desync_frames_bucket_total{bucket="3_10"} 579
telemt_desync_frames_bucket_total{bucket="gt_10"} 603
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 219
telemt_me_writer_close_signal_drop_total 151
telemt_me_writer_close_signal_channel_full_total 1
telemt_me_writer_removed_unexpected_total 6689
telemt_me_writer_restored_same_endpoint_total 6618
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 62
telemt_user_connections_total{user="hello"} 705519
telemt_user_connections_current{user="hello"} 510
telemt_user_octets_from_client{user="hello"} 7667535879 (7.14 GB)
telemt_user_octets_to_client{user="hello"} 146571734990 (136.51 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 150
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 50158.7 (13h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2084348
telemt_connections_bad_total 122898
telemt_connections_current 1359
telemt_connections_me_current 1359
telemt_handshake_timeouts_total 38307
telemt_upstream_connect_attempt_total 9012
telemt_upstream_connect_success_total 8950
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 9012
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4819
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4094
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6492
telemt_me_reconnect_success_total 6447
telemt_me_reader_eof_total 6809
telemt_me_idle_close_by_peer_total 6809
telemt_me_route_drop_no_conn_total 757487
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1779824
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9341
telemt_desync_full_logged_total 3010
telemt_desync_suppressed_total 6331
telemt_desync_frames_bucket_total{bucket="1_2"} 1776
telemt_desync_frames_bucket_total{bucket="3_10"} 3268
telemt_desync_frames_bucket_total{bucket="gt_10"} 4297
telemt_pool_swap_total 50
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6542
telemt_me_writer_restored_same_endpoint_total 6430
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 95
telemt_user_connections_total{user="hello"} 1778932
telemt_user_connections_current{user="hello"} 1359
telemt_user_octets_from_client{user="hello"} 30304333388 (28.22 GB)
telemt_user_octets_to_client{user="hello"} 908311046124 (845.93 GB)
telemt_user_unique_ips_current{user="hello"} 540
telemt_user_unique_ips_recent_window{user="hello"} 118
```