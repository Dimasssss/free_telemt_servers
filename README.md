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

# Server Metrics 2026-03-20 04:37:39 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 40804.1 (11h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 759683
telemt_connections_bad_total 51628
telemt_connections_current 1229
telemt_connections_me_current 1229
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 17612
telemt_upstream_connect_attempt_total 8138
telemt_upstream_connect_success_total 8043
telemt_upstream_connect_fail_total 95
telemt_upstream_connect_attempts_per_request{bucket="1"} 8138
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4498
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3517
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 95
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 4927
telemt_me_reconnect_success_total 4885
telemt_me_reader_eof_total 5173
telemt_me_idle_close_by_peer_total 5172
telemt_me_route_drop_no_conn_total 213345
telemt_me_route_drop_channel_closed_total 68
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 606333
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3259
telemt_desync_full_logged_total 1162
telemt_desync_suppressed_total 2097
telemt_desync_frames_bucket_total{bucket="1_2"} 637
telemt_desync_frames_bucket_total{bucket="3_10"} 1257
telemt_desync_frames_bucket_total{bucket="gt_10"} 1365
telemt_pool_swap_total 45
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 4932
telemt_me_writer_restored_same_endpoint_total 4872
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 47
telemt_user_connections_total{user="hello"} 607748
telemt_user_connections_current{user="hello"} 1229
telemt_user_octets_from_client{user="hello"} 32004200228 (29.81 GB)
telemt_user_octets_to_client{user="hello"} 206283023501 (192.12 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 466
telemt_user_unique_ips_recent_window{user="hello"} 169
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 57259.5 (15h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3501805
telemt_connections_bad_total 284555
telemt_connections_current 2997
telemt_connections_me_current 2997
telemt_handshake_timeouts_total 75586
telemt_upstream_connect_attempt_total 10938
telemt_upstream_connect_success_total 10739
telemt_upstream_connect_fail_total 199
telemt_upstream_connect_attempts_per_request{bucket="1"} 10938
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6095
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 199
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10920
telemt_me_reconnect_success_total 6670
telemt_me_reader_eof_total 7138
telemt_me_idle_close_by_peer_total 7138
telemt_me_route_drop_no_conn_total 1609732
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2893192
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12084
telemt_desync_full_logged_total 4039
telemt_desync_suppressed_total 8045
telemt_desync_frames_bucket_total{bucket="1_2"} 2313
telemt_desync_frames_bucket_total{bucket="3_10"} 4696
telemt_desync_frames_bucket_total{bucket="gt_10"} 5075
telemt_pool_swap_total 51
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 55
telemt_me_writer_removed_unexpected_total 6885
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6615
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 215
telemt_user_connections_total{user="hello"} 2892861
telemt_user_connections_current{user="hello"} 2997
telemt_user_octets_from_client{user="hello"} 43992168282 (40.97 GB)
telemt_user_octets_to_client{user="hello"} 1092749305778 (1017.70 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1130
telemt_user_unique_ips_recent_window{user="hello"} 385
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 57237.8 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3228388
telemt_connections_bad_total 487151
telemt_connections_current 2564
telemt_connections_me_current 2564
telemt_handshake_timeouts_total 50809
telemt_upstream_connect_attempt_total 9325
telemt_upstream_connect_success_total 9260
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9325
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4697
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4546
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7357
telemt_me_reconnect_success_total 6417
telemt_me_reader_eof_total 6757
telemt_me_idle_close_by_peer_total 6756
telemt_me_route_drop_no_conn_total 2007116
telemt_me_route_drop_channel_closed_total 178
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2258480
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8320
telemt_desync_full_logged_total 2561
telemt_desync_suppressed_total 5759
telemt_desync_frames_bucket_total{bucket="1_2"} 2056
telemt_desync_frames_bucket_total{bucket="3_10"} 3172
telemt_desync_frames_bucket_total{bucket="gt_10"} 3092
telemt_pool_swap_total 57
telemt_me_writer_close_signal_drop_total 74
telemt_me_writer_removed_unexpected_total 6484
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6416
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 2253507
telemt_user_connections_current{user="hello"} 2564
telemt_user_octets_from_client{user="hello"} 34278113380 (31.92 GB)
telemt_user_octets_to_client{user="hello"} 899602143684 (837.82 GB)
telemt_user_unique_ips_current{user="hello"} 889
telemt_user_unique_ips_recent_window{user="hello"} 312
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 57225.5 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2921442
telemt_connections_bad_total 221481
telemt_connections_current 2110
telemt_connections_me_current 2110
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 36506
telemt_upstream_connect_attempt_total 63309
telemt_upstream_connect_success_total 58750
telemt_upstream_connect_fail_total 4559
telemt_upstream_connect_attempts_per_request{bucket="1"} 63309
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49648
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8526
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 551
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4559
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9699
telemt_me_reconnect_success_total 6768
telemt_me_reader_eof_total 7063
telemt_me_idle_close_by_peer_total 7062
telemt_me_route_drop_no_conn_total 1989510
telemt_me_route_drop_channel_closed_total 67
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2368760
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9035
telemt_desync_full_logged_total 2890
telemt_desync_suppressed_total 6145
telemt_desync_frames_bucket_total{bucket="1_2"} 2186
telemt_desync_frames_bucket_total{bucket="3_10"} 3315
telemt_desync_frames_bucket_total{bucket="gt_10"} 3534
telemt_pool_swap_total 44
telemt_me_writer_close_signal_drop_total 541
telemt_me_writer_removed_unexpected_total 7449
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6764
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 681
telemt_user_connections_total{user="hello"} 2415953
telemt_user_connections_current{user="hello"} 2110
telemt_user_octets_from_client{user="hello"} 38345516945 (35.71 GB)
telemt_user_octets_to_client{user="hello"} 721893673259 (672.32 GB)
telemt_user_msgs_from_client{user="hello"} 254085
telemt_user_msgs_to_client{user="hello"} 1776413
telemt_user_unique_ips_current{user="hello"} 792
telemt_user_unique_ips_recent_window{user="hello"} 268
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 110948.6 (30h 49m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6673636
telemt_connections_bad_total 1177835
telemt_connections_current 2592
telemt_connections_me_current 2592
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 119187
telemt_upstream_connect_attempt_total 129319
telemt_upstream_connect_success_total 96020
telemt_upstream_connect_fail_total 33299
telemt_upstream_connect_attempts_per_request{bucket="1"} 129319
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81236
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13347
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33299
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 79848
telemt_me_reconnect_success_total 14170
telemt_me_reader_eof_total 15247
telemt_me_idle_close_by_peer_total 15233
telemt_me_route_drop_no_conn_total 2882092
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4695199
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
telemt_desync_total 20322
telemt_desync_full_logged_total 6468
telemt_desync_suppressed_total 13854
telemt_desync_frames_bucket_total{bucket="1_2"} 3587
telemt_desync_frames_bucket_total{bucket="3_10"} 8409
telemt_desync_frames_bucket_total{bucket="gt_10"} 8326
telemt_pool_swap_total 99
telemt_me_writer_removed_unexpected_total 14493
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14145
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 323
telemt_user_connections_total{user="hello"} 4770269
telemt_user_connections_current{user="hello"} 2592
telemt_user_octets_from_client{user="hello"} 75521171768 (70.33 GB)
telemt_user_octets_to_client{user="hello"} 1870999598252 (1.70 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 936
telemt_user_unique_ips_recent_window{user="hello"} 318
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 57188.7 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1371470
telemt_connections_bad_total 98435
telemt_connections_current 494
telemt_connections_me_current 494
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13907
telemt_upstream_connect_attempt_total 13771
telemt_upstream_connect_success_total 13441
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13771
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5581
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
telemt_me_route_drop_no_conn_total 473323
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
telemt_desync_total 1493
telemt_desync_full_logged_total 566
telemt_desync_suppressed_total 927
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 645
telemt_desync_frames_bucket_total{bucket="gt_10"} 614
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
telemt_user_connections_total{user="hello"} 1201694
telemt_user_connections_current{user="hello"} 494
telemt_user_octets_from_client{user="hello"} 8379945291 (7.80 GB)
telemt_user_octets_to_client{user="hello"} 146614806066 (136.55 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 191
telemt_user_unique_ips_recent_window{user="hello"} 162
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 57190.0 (15h 53m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2289880
telemt_connections_bad_total 148856
telemt_connections_current 2396
telemt_connections_me_current 2396
telemt_handshake_timeouts_total 43191
telemt_upstream_connect_attempt_total 10277
telemt_upstream_connect_success_total 10211
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10277
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5505
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4669
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7408
telemt_me_reconnect_success_total 7359
telemt_me_reader_eof_total 7775
telemt_me_idle_close_by_peer_total 7775
telemt_me_route_drop_no_conn_total 818486
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1933208
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9826
telemt_desync_full_logged_total 3179
telemt_desync_suppressed_total 6647
telemt_desync_frames_bucket_total{bucket="1_2"} 1932
telemt_desync_frames_bucket_total{bucket="3_10"} 3443
telemt_desync_frames_bucket_total{bucket="gt_10"} 4451
telemt_pool_swap_total 58
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7463
telemt_me_writer_restored_same_endpoint_total 7342
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 104
telemt_user_connections_total{user="hello"} 1931910
telemt_user_connections_current{user="hello"} 2396
telemt_user_octets_from_client{user="hello"} 41495855556 (38.65 GB)
telemt_user_octets_to_client{user="hello"} 1010556610768 (941.15 GB)
telemt_user_unique_ips_current{user="hello"} 836
telemt_user_unique_ips_recent_window{user="hello"} 264
```