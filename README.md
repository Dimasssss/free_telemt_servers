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

# Server Metrics 2026-03-20 02:04:46 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 31630.9 (8h 47m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 592508
telemt_connections_bad_total 37903
telemt_connections_current 860
telemt_connections_me_current 860
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9406
telemt_upstream_connect_attempt_total 6628
telemt_upstream_connect_success_total 6542
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 6628
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3743
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3858
telemt_me_reconnect_success_total 3823
telemt_me_reader_eof_total 4035
telemt_me_idle_close_by_peer_total 4034
telemt_me_route_drop_no_conn_total 169081
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 472984
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2199
telemt_desync_full_logged_total 793
telemt_desync_suppressed_total 1406
telemt_desync_frames_bucket_total{bucket="1_2"} 442
telemt_desync_frames_bucket_total{bucket="3_10"} 761
telemt_desync_frames_bucket_total{bucket="gt_10"} 996
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3851
telemt_me_writer_restored_same_endpoint_total 3810
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 474412
telemt_user_connections_current{user="hello"} 860
telemt_user_octets_from_client{user="hello"} 30051652252 (27.99 GB)
telemt_user_octets_to_client{user="hello"} 166222228089 (154.81 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 342
telemt_user_unique_ips_recent_window{user="hello"} 106
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 48086.3 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3031815
telemt_connections_bad_total 128935
telemt_connections_current 1477
telemt_connections_me_current 1477
telemt_handshake_timeouts_total 66880
telemt_upstream_connect_attempt_total 9549
telemt_upstream_connect_success_total 9389
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 9549
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5421
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3910
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10000
telemt_me_reconnect_success_total 5756
telemt_me_reader_eof_total 6160
telemt_me_idle_close_by_peer_total 6160
telemt_me_route_drop_no_conn_total 1510500
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2598251
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11244
telemt_desync_full_logged_total 3704
telemt_desync_suppressed_total 7540
telemt_desync_frames_bucket_total{bucket="1_2"} 2147
telemt_desync_frames_bucket_total{bucket="3_10"} 4398
telemt_desync_frames_bucket_total{bucket="gt_10"} 4699
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 52
telemt_me_writer_removed_unexpected_total 5953
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5701
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 197
telemt_user_connections_total{user="hello"} 2598028
telemt_user_connections_current{user="hello"} 1477
telemt_user_octets_from_client{user="hello"} 39627175666 (36.91 GB)
telemt_user_octets_to_client{user="hello"} 958850104206 (893.00 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 688
telemt_user_unique_ips_recent_window{user="hello"} 161
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 48065.5 (13h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2977503
telemt_connections_bad_total 476850
telemt_connections_current 1283
telemt_connections_me_current 1283
telemt_handshake_timeouts_total 44321
telemt_upstream_connect_attempt_total 7800
telemt_upstream_connect_success_total 7742
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 7800
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3938
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3787
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6270
telemt_me_reconnect_success_total 5336
telemt_me_reader_eof_total 5603
telemt_me_idle_close_by_peer_total 5602
telemt_me_route_drop_no_conn_total 1927115
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2053124
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7700
telemt_desync_full_logged_total 2337
telemt_desync_suppressed_total 5363
telemt_desync_frames_bucket_total{bucket="1_2"} 1903
telemt_desync_frames_bucket_total{bucket="3_10"} 2928
telemt_desync_frames_bucket_total{bucket="gt_10"} 2869
telemt_pool_swap_total 47
telemt_me_writer_close_signal_drop_total 70
telemt_me_writer_removed_unexpected_total 5389
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5335
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 2048745
telemt_user_connections_current{user="hello"} 1283
telemt_user_octets_from_client{user="hello"} 30223849528 (28.15 GB)
telemt_user_octets_to_client{user="hello"} 788594177528 (734.44 GB)
telemt_user_unique_ips_current{user="hello"} 536
telemt_user_unique_ips_recent_window{user="hello"} 137
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 48052.2 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2605954
telemt_connections_bad_total 147380
telemt_connections_current 1098
telemt_connections_me_current 1098
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31462
telemt_upstream_connect_attempt_total 55708
telemt_upstream_connect_success_total 51422
telemt_upstream_connect_fail_total 4286
telemt_upstream_connect_attempts_per_request{bucket="1"} 55708
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43262
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7606
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 529
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4286
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8613
telemt_me_reconnect_success_total 5769
telemt_me_reader_eof_total 6000
telemt_me_idle_close_by_peer_total 5999
telemt_me_route_drop_no_conn_total 1869265
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2156794
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8365
telemt_desync_full_logged_total 2645
telemt_desync_suppressed_total 5720
telemt_desync_frames_bucket_total{bucket="1_2"} 2062
telemt_desync_frames_bucket_total{bucket="3_10"} 3042
telemt_desync_frames_bucket_total{bucket="gt_10"} 3261
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6397
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5765
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 628
telemt_user_connections_total{user="hello"} 2198867
telemt_user_connections_current{user="hello"} 1098
telemt_user_octets_from_client{user="hello"} 35781387613 (33.32 GB)
telemt_user_octets_to_client{user="hello"} 619320406601 (576.79 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 452
telemt_user_unique_ips_recent_window{user="hello"} 117
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 101775.5 (28h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6300173
telemt_connections_bad_total 1046152
telemt_connections_current 1309
telemt_connections_me_current 1309
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 113951
telemt_upstream_connect_attempt_total 127737
telemt_upstream_connect_success_total 94451
telemt_upstream_connect_fail_total 33286
telemt_upstream_connect_attempts_per_request{bucket="1"} 127737
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80435
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12583
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33286
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78720
telemt_me_reconnect_success_total 13050
telemt_me_reader_eof_total 14052
telemt_me_idle_close_by_peer_total 14038
telemt_me_route_drop_no_conn_total 2804356
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4469350
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
telemt_desync_total 19583
telemt_desync_full_logged_total 6208
telemt_desync_suppressed_total 13375
telemt_desync_frames_bucket_total{bucket="1_2"} 3450
telemt_desync_frames_bucket_total{bucket="3_10"} 8062
telemt_desync_frames_bucket_total{bucket="gt_10"} 8071
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 13359
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13025
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 4544562
telemt_user_connections_current{user="hello"} 1309
telemt_user_octets_from_client{user="hello"} 72681067352 (67.69 GB)
telemt_user_octets_to_client{user="hello"} 1746019426660 (1.59 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 556
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 48015.4 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 735573
telemt_connections_bad_total 77851
telemt_connections_current 497
telemt_connections_me_current 497
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13093
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
telemt_me_route_drop_no_conn_total 471598
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
telemt_desync_total 1397
telemt_desync_full_logged_total 523
telemt_desync_suppressed_total 874
telemt_desync_frames_bucket_total{bucket="1_2"} 218
telemt_desync_frames_bucket_total{bucket="3_10"} 576
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
telemt_user_connections_total{user="hello"} 594127
telemt_user_connections_current{user="hello"} 497
telemt_user_octets_from_client{user="hello"} 7421331507 (6.91 GB)
telemt_user_octets_to_client{user="hello"} 146471869478 (136.41 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 168
telemt_user_unique_ips_recent_window{user="hello"} 100
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 48017.0 (13h 20m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2045159
telemt_connections_bad_total 120309
telemt_connections_current 1328
telemt_connections_me_current 1328
telemt_handshake_timeouts_total 37886
telemt_upstream_connect_attempt_total 8619
telemt_upstream_connect_success_total 8559
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8619
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4599
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3923
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6187
telemt_me_reconnect_success_total 6144
telemt_me_reader_eof_total 6487
telemt_me_idle_close_by_peer_total 6487
telemt_me_route_drop_no_conn_total 747861
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1755086
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9279
telemt_desync_full_logged_total 2988
telemt_desync_suppressed_total 6291
telemt_desync_frames_bucket_total{bucket="1_2"} 1759
telemt_desync_frames_bucket_total{bucket="3_10"} 3251
telemt_desync_frames_bucket_total{bucket="gt_10"} 4269
telemt_pool_swap_total 48
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6235
telemt_me_writer_restored_same_endpoint_total 6127
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 91
telemt_user_connections_total{user="hello"} 1754194
telemt_user_connections_current{user="hello"} 1328
telemt_user_octets_from_client{user="hello"} 29989174944 (27.93 GB)
telemt_user_octets_to_client{user="hello"} 889915076064 (828.80 GB)
telemt_user_unique_ips_current{user="hello"} 516
telemt_user_unique_ips_recent_window{user="hello"} 118
```