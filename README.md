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

# Server Metrics 2026-03-20 02:09:52 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 31937.6 (8h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 597527
telemt_connections_bad_total 38160
telemt_connections_current 838
telemt_connections_me_current 838
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 9814
telemt_upstream_connect_attempt_total 6682
telemt_upstream_connect_success_total 6596
telemt_upstream_connect_fail_total 86
telemt_upstream_connect_attempts_per_request{bucket="1"} 6682
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3761
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2807
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 86
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3912
telemt_me_reconnect_success_total 3876
telemt_me_reader_eof_total 4092
telemt_me_idle_close_by_peer_total 4091
telemt_me_route_drop_no_conn_total 170939
telemt_me_route_drop_channel_closed_total 58
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 476764
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2219
telemt_desync_full_logged_total 800
telemt_desync_suppressed_total 1419
telemt_desync_frames_bucket_total{bucket="1_2"} 445
telemt_desync_frames_bucket_total{bucket="3_10"} 772
telemt_desync_frames_bucket_total{bucket="gt_10"} 1002
telemt_pool_swap_total 35
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3905
telemt_me_writer_restored_same_endpoint_total 3863
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 478197
telemt_user_connections_current{user="hello"} 838
telemt_user_octets_from_client{user="hello"} 30116472364 (28.05 GB)
telemt_user_octets_to_client{user="hello"} 167373117189 (155.88 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 343
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 48392.3 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3039801
telemt_connections_bad_total 130915
telemt_connections_current 1518
telemt_connections_me_current 1518
telemt_handshake_timeouts_total 67120
telemt_upstream_connect_attempt_total 9567
telemt_upstream_connect_success_total 9407
telemt_upstream_connect_fail_total 160
telemt_upstream_connect_attempts_per_request{bucket="1"} 9567
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5428
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3921
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 58
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 160
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 10018
telemt_me_reconnect_success_total 5774
telemt_me_reader_eof_total 6180
telemt_me_idle_close_by_peer_total 6180
telemt_me_route_drop_no_conn_total 1512252
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2603905
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11257
telemt_desync_full_logged_total 3710
telemt_desync_suppressed_total 7547
telemt_desync_frames_bucket_total{bucket="1_2"} 2152
telemt_desync_frames_bucket_total{bucket="3_10"} 4400
telemt_desync_frames_bucket_total{bucket="gt_10"} 4705
telemt_pool_swap_total 41
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 52
telemt_me_writer_removed_unexpected_total 5973
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5719
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 199
telemt_user_connections_total{user="hello"} 2603678
telemt_user_connections_current{user="hello"} 1518
telemt_user_octets_from_client{user="hello"} 39777105302 (37.05 GB)
telemt_user_octets_to_client{user="hello"} 962219297898 (896.14 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 673
telemt_user_unique_ips_recent_window{user="hello"} 130
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 48370.3 (13h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2983358
telemt_connections_bad_total 476960
telemt_connections_current 1192
telemt_connections_me_current 1192
telemt_handshake_timeouts_total 44630
telemt_upstream_connect_attempt_total 7833
telemt_upstream_connect_success_total 7775
telemt_upstream_connect_fail_total 58
telemt_upstream_connect_attempts_per_request{bucket="1"} 7833
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3951
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3807
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 58
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6303
telemt_me_reconnect_success_total 5369
telemt_me_reader_eof_total 5636
telemt_me_idle_close_by_peer_total 5635
telemt_me_route_drop_no_conn_total 1928519
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2057701
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7724
telemt_desync_full_logged_total 2345
telemt_desync_suppressed_total 5379
telemt_desync_frames_bucket_total{bucket="1_2"} 1904
telemt_desync_frames_bucket_total{bucket="3_10"} 2940
telemt_desync_frames_bucket_total{bucket="gt_10"} 2880
telemt_pool_swap_total 47
telemt_me_writer_close_signal_drop_total 70
telemt_me_writer_removed_unexpected_total 5422
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5368
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 2053322
telemt_user_connections_current{user="hello"} 1192
telemt_user_octets_from_client{user="hello"} 30265042356 (28.19 GB)
telemt_user_octets_to_client{user="hello"} 790705106436 (736.40 GB)
telemt_user_unique_ips_current{user="hello"} 527
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 48358.2 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2616818
telemt_connections_bad_total 153688
telemt_connections_current 1165
telemt_connections_me_current 1165
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31532
telemt_upstream_connect_attempt_total 55730
telemt_upstream_connect_success_total 51444
telemt_upstream_connect_fail_total 4286
telemt_upstream_connect_attempts_per_request{bucket="1"} 55730
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43271
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 529
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4286
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8635
telemt_me_reconnect_success_total 5791
telemt_me_reader_eof_total 6024
telemt_me_idle_close_by_peer_total 6023
telemt_me_route_drop_no_conn_total 1870529
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2160705
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8371
telemt_desync_full_logged_total 2648
telemt_desync_suppressed_total 5723
telemt_desync_frames_bucket_total{bucket="1_2"} 2062
telemt_desync_frames_bucket_total{bucket="3_10"} 3045
telemt_desync_frames_bucket_total{bucket="gt_10"} 3264
telemt_pool_swap_total 34
telemt_me_writer_close_signal_drop_total 478
telemt_me_writer_removed_unexpected_total 6421
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5787
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 630
telemt_user_connections_total{user="hello"} 2202777
telemt_user_connections_current{user="hello"} 1165
telemt_user_octets_from_client{user="hello"} 35805248765 (33.35 GB)
telemt_user_octets_to_client{user="hello"} 620458743509 (577.85 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 453
telemt_user_unique_ips_recent_window{user="hello"} 111
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 102081.4 (28h 21m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6305850
telemt_connections_bad_total 1046831
telemt_connections_current 1258
telemt_connections_me_current 1258
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 114173
telemt_upstream_connect_attempt_total 127823
telemt_upstream_connect_success_total 94536
telemt_upstream_connect_fail_total 33287
telemt_upstream_connect_attempts_per_request{bucket="1"} 127823
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80479
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1434
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33287
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78794
telemt_me_reconnect_success_total 13123
telemt_me_reader_eof_total 14133
telemt_me_idle_close_by_peer_total 14119
telemt_me_route_drop_no_conn_total 2805958
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4473965
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
telemt_desync_total 19593
telemt_desync_full_logged_total 6211
telemt_desync_suppressed_total 13382
telemt_desync_frames_bucket_total{bucket="1_2"} 3451
telemt_desync_frames_bucket_total{bucket="3_10"} 8071
telemt_desync_frames_bucket_total{bucket="gt_10"} 8071
telemt_pool_swap_total 89
telemt_me_writer_removed_unexpected_total 13432
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 13098
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 4549177
telemt_user_connections_current{user="hello"} 1258
telemt_user_octets_from_client{user="hello"} 72720195184 (67.73 GB)
telemt_user_octets_to_client{user="hello"} 1747951258264 (1.59 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 533
telemt_user_unique_ips_recent_window{user="hello"} 125
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 48321.3 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 746984
telemt_connections_bad_total 78541
telemt_connections_current 446
telemt_connections_me_current 446
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13097
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
telemt_me_route_drop_no_conn_total 471793
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
telemt_user_connections_total{user="hello"} 604780
telemt_user_connections_current{user="hello"} 446
telemt_user_octets_from_client{user="hello"} 7439587027 (6.93 GB)
telemt_user_octets_to_client{user="hello"} 146473321210 (136.41 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 152
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 48322.8 (13h 25m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2050404
telemt_connections_bad_total 120352
telemt_connections_current 1271
telemt_connections_me_current 1271
telemt_handshake_timeouts_total 37949
telemt_upstream_connect_attempt_total 8656
telemt_upstream_connect_success_total 8596
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8656
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3936
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 6224
telemt_me_reconnect_success_total 6180
telemt_me_reader_eof_total 6524
telemt_me_idle_close_by_peer_total 6524
telemt_me_route_drop_no_conn_total 749022
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1758452
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9293
telemt_desync_full_logged_total 2991
telemt_desync_suppressed_total 6302
telemt_desync_frames_bucket_total{bucket="1_2"} 1761
telemt_desync_frames_bucket_total{bucket="3_10"} 3257
telemt_desync_frames_bucket_total{bucket="gt_10"} 4275
telemt_pool_swap_total 48
telemt_me_writer_close_signal_drop_total 41
telemt_me_writer_removed_unexpected_total 6272
telemt_me_writer_restored_same_endpoint_total 6163
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 92
telemt_user_connections_total{user="hello"} 1757560
telemt_user_connections_current{user="hello"} 1271
telemt_user_octets_from_client{user="hello"} 30037361504 (27.97 GB)
telemt_user_octets_to_client{user="hello"} 892007044916 (830.75 GB)
telemt_user_unique_ips_current{user="hello"} 510
telemt_user_unique_ips_recent_window{user="hello"} 104
```