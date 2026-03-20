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

# Server Metrics 2026-03-20 01:44:22 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 30406.9 (8h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 571609
telemt_connections_bad_total 36857
telemt_connections_current 790
telemt_connections_me_current 790
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8919
telemt_upstream_connect_attempt_total 6404
telemt_upstream_connect_success_total 6320
telemt_upstream_connect_fail_total 84
telemt_upstream_connect_attempts_per_request{bucket="1"} 6404
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3634
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 28
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 84
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 3722
telemt_me_reconnect_success_total 3687
telemt_me_reader_eof_total 3888
telemt_me_idle_close_by_peer_total 3887
telemt_me_route_drop_no_conn_total 164709
telemt_me_route_drop_channel_closed_total 57
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 456714
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 2144
telemt_desync_full_logged_total 768
telemt_desync_suppressed_total 1376
telemt_desync_frames_bucket_total{bucket="1_2"} 432
telemt_desync_frames_bucket_total{bucket="3_10"} 736
telemt_desync_frames_bucket_total{bucket="gt_10"} 976
telemt_pool_swap_total 33
telemt_me_writer_close_signal_drop_total 39
telemt_me_writer_removed_unexpected_total 3712
telemt_me_writer_restored_same_endpoint_total 3674
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 25
telemt_user_connections_total{user="hello"} 458143
telemt_user_connections_current{user="hello"} 790
telemt_user_octets_from_client{user="hello"} 29798189988 (27.75 GB)
telemt_user_octets_to_client{user="hello"} 162043485001 (150.91 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 323
telemt_user_unique_ips_recent_window{user="hello"} 89
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 46861.6 (13h 1m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3006071
telemt_connections_bad_total 125887
telemt_connections_current 1398
telemt_connections_me_current 1398
telemt_handshake_timeouts_total 66267
telemt_upstream_connect_attempt_total 9294
telemt_upstream_connect_success_total 9138
telemt_upstream_connect_fail_total 156
telemt_upstream_connect_attempts_per_request{bucket="1"} 9294
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5310
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3771
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 156
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 9818
telemt_me_reconnect_success_total 5576
telemt_me_reader_eof_total 5968
telemt_me_idle_close_by_peer_total 5968
telemt_me_route_drop_no_conn_total 1505005
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2576557
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 11159
telemt_desync_full_logged_total 3675
telemt_desync_suppressed_total 7484
telemt_desync_frames_bucket_total{bucket="1_2"} 2137
telemt_desync_frames_bucket_total{bucket="3_10"} 4363
telemt_desync_frames_bucket_total{bucket="gt_10"} 4659
telemt_pool_swap_total 39
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 51
telemt_me_writer_removed_unexpected_total 5772
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 5521
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 196
telemt_user_connections_total{user="hello"} 2576337
telemt_user_connections_current{user="hello"} 1398
telemt_user_octets_from_client{user="hello"} 39364289370 (36.66 GB)
telemt_user_octets_to_client{user="hello"} 944171293138 (879.33 GB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 658
telemt_user_unique_ips_recent_window{user="hello"} 153
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 46839.6 (13h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2957422
telemt_connections_bad_total 475600
telemt_connections_current 1126
telemt_connections_me_current 1126
telemt_handshake_timeouts_total 43520
telemt_upstream_connect_attempt_total 7539
telemt_upstream_connect_success_total 7481
telemt_upstream_connect_fail_total 57
telemt_upstream_connect_attempts_per_request{bucket="1"} 7538
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3816
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3648
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 57
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 6086
telemt_me_reconnect_success_total 5153
telemt_me_reader_eof_total 5404
telemt_me_idle_close_by_peer_total 5403
telemt_me_route_drop_no_conn_total 1921844
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2038308
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 7658
telemt_desync_full_logged_total 2327
telemt_desync_suppressed_total 5331
telemt_desync_frames_bucket_total{bucket="1_2"} 1887
telemt_desync_frames_bucket_total{bucket="3_10"} 2916
telemt_desync_frames_bucket_total{bucket="gt_10"} 2855
telemt_pool_swap_total 45
telemt_me_writer_close_signal_drop_total 69
telemt_me_writer_removed_unexpected_total 5204
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 5152
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 2033930
telemt_user_connections_current{user="hello"} 1126
telemt_user_octets_from_client{user="hello"} 30059216440 (27.99 GB)
telemt_user_octets_to_client{user="hello"} 778825296812 (725.34 GB)
telemt_user_unique_ips_current{user="hello"} 485
telemt_user_unique_ips_recent_window{user="hello"} 97
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 46827.4 (13h 0m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2571695
telemt_connections_bad_total 130805
telemt_connections_current 1116
telemt_connections_me_current 1116
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 31221
telemt_upstream_connect_attempt_total 55472
telemt_upstream_connect_success_total 51195
telemt_upstream_connect_fail_total 4277
telemt_upstream_connect_attempts_per_request{bucket="1"} 55472
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43131
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7511
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 528
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4277
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 8466
telemt_me_reconnect_success_total 5626
telemt_me_reader_eof_total 5845
telemt_me_idle_close_by_peer_total 5844
telemt_me_route_drop_no_conn_total 1864872
telemt_me_route_drop_channel_closed_total 21
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2141762
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8350
telemt_desync_full_logged_total 2635
telemt_desync_suppressed_total 5715
telemt_desync_frames_bucket_total{bucket="1_2"} 2061
telemt_desync_frames_bucket_total{bucket="3_10"} 3034
telemt_desync_frames_bucket_total{bucket="gt_10"} 3255
telemt_pool_swap_total 32
telemt_me_writer_close_signal_drop_total 477
telemt_me_writer_removed_unexpected_total 6251
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 5622
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 2183837
telemt_user_connections_current{user="hello"} 1116
telemt_user_octets_from_client{user="hello"} 35628959949 (33.18 GB)
telemt_user_octets_to_client{user="hello"} 614464028961 (572.26 GB)
telemt_user_msgs_from_client{user="hello"} 240837
telemt_user_msgs_to_client{user="hello"} 1741640
telemt_user_unique_ips_current{user="hello"} 432
telemt_user_unique_ips_recent_window{user="hello"} 119
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 100550.6 (27h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6277276
telemt_connections_bad_total 1043519
telemt_connections_current 1246
telemt_connections_me_current 1246
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 113571
telemt_upstream_connect_attempt_total 127502
telemt_upstream_connect_success_total 94217
telemt_upstream_connect_fail_total 33285
telemt_upstream_connect_attempts_per_request{bucket="1"} 127502
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 80311
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12473
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1433
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33285
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 78562
telemt_me_reconnect_success_total 12892
telemt_me_reader_eof_total 13886
telemt_me_idle_close_by_peer_total 13872
telemt_me_route_drop_no_conn_total 2798714
telemt_me_route_drop_channel_closed_total 18
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4450203
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
telemt_desync_total 19555
telemt_desync_full_logged_total 6195
telemt_desync_suppressed_total 13360
telemt_desync_frames_bucket_total{bucket="1_2"} 3439
telemt_desync_frames_bucket_total{bucket="3_10"} 8051
telemt_desync_frames_bucket_total{bucket="gt_10"} 8065
telemt_pool_swap_total 87
telemt_me_writer_removed_unexpected_total 13201
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 12867
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 309
telemt_user_connections_total{user="hello"} 4525417
telemt_user_connections_current{user="hello"} 1246
telemt_user_octets_from_client{user="hello"} 72537081848 (67.56 GB)
telemt_user_octets_to_client{user="hello"} 1741377549400 (1.58 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 545
telemt_user_unique_ips_recent_window{user="hello"} 133
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 46790.6 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 713270
telemt_connections_bad_total 76686
telemt_connections_current 366
telemt_connections_me_current 366
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 13028
telemt_upstream_connect_attempt_total 13712
telemt_upstream_connect_success_total 13382
telemt_upstream_connect_fail_total 330
telemt_upstream_connect_attempts_per_request{bucket="1"} 13712
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5549
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6992
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 180
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 661
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 330
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 434
telemt_me_reconnect_attempts_total 6721
telemt_me_reconnect_success_total 6613
telemt_me_reader_eof_total 6937
telemt_me_idle_close_by_peer_total 6934
telemt_me_route_drop_no_conn_total 470503
telemt_me_route_drop_channel_closed_total 144
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 585225
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
telemt_me_writer_removed_unexpected_total 6674
telemt_me_writer_restored_same_endpoint_total 6604
telemt_me_writer_restored_fallback_total 9
telemt_me_no_writer_failfast_total 1203
telemt_me_async_recovery_trigger_total 1464
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 573371
telemt_user_connections_current{user="hello"} 366
telemt_user_octets_from_client{user="hello"} 7368572347 (6.86 GB)
telemt_user_octets_to_client{user="hello"} 146269552746 (136.22 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 159
telemt_user_unique_ips_recent_window{user="hello"} 48
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 46791.9 (12h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2022816
telemt_connections_bad_total 120016
telemt_connections_current 1170
telemt_connections_me_current 1170
telemt_handshake_timeouts_total 37644
telemt_upstream_connect_attempt_total 8343
telemt_upstream_connect_success_total 8283
telemt_upstream_connect_fail_total 60
telemt_upstream_connect_attempts_per_request{bucket="1"} 8343
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4468
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3778
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 60
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 5999
telemt_me_reconnect_success_total 5956
telemt_me_reader_eof_total 6284
telemt_me_idle_close_by_peer_total 6284
telemt_me_route_drop_no_conn_total 744138
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1742593
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9241
telemt_desync_full_logged_total 2968
telemt_desync_suppressed_total 6273
telemt_desync_frames_bucket_total{bucket="1_2"} 1739
telemt_desync_frames_bucket_total{bucket="3_10"} 3239
telemt_desync_frames_bucket_total{bucket="gt_10"} 4263
telemt_pool_swap_total 46
telemt_me_writer_close_signal_drop_total 40
telemt_me_writer_removed_unexpected_total 6045
telemt_me_writer_restored_same_endpoint_total 5939
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 1741700
telemt_user_connections_current{user="hello"} 1170
telemt_user_octets_from_client{user="hello"} 29733334412 (27.69 GB)
telemt_user_octets_to_client{user="hello"} 883023626580 (822.38 GB)
telemt_user_unique_ips_current{user="hello"} 471
telemt_user_unique_ips_recent_window{user="hello"} 96
```