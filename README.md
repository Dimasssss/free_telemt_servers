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

# Server Metrics 2026-03-20 05:13:19 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.24

telemt_uptime_seconds 42943.9 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 815877
telemt_connections_bad_total 54367
telemt_connections_current 1251
telemt_connections_me_current 1251
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 18665
telemt_upstream_connect_attempt_total 8449
telemt_upstream_connect_success_total 8351
telemt_upstream_connect_fail_total 98
telemt_upstream_connect_attempts_per_request{bucket="1"} 8449
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3681
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 29
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 98
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 24
telemt_me_reconnect_attempts_total 5149
telemt_me_reconnect_success_total 5106
telemt_me_reader_eof_total 5409
telemt_me_idle_close_by_peer_total 5408
telemt_me_route_drop_no_conn_total 227609
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 655295
telemt_me_writer_pick_total{mode="p2c",result="full"} 12
telemt_me_writer_pick_total{mode="p2c",result="closed"} 25
telemt_me_endpoint_quarantine_total 21
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 3482
telemt_desync_full_logged_total 1252
telemt_desync_suppressed_total 2230
telemt_desync_frames_bucket_total{bucket="1_2"} 671
telemt_desync_frames_bucket_total{bucket="3_10"} 1358
telemt_desync_frames_bucket_total{bucket="gt_10"} 1453
telemt_pool_swap_total 47
telemt_me_writer_close_signal_drop_total 44
telemt_me_writer_removed_unexpected_total 5157
telemt_me_writer_restored_same_endpoint_total 5093
telemt_me_writer_restored_fallback_total 13
telemt_me_no_writer_failfast_total 20
telemt_me_async_recovery_trigger_total 447
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 656810
telemt_user_connections_current{user="hello"} 1251
telemt_user_octets_from_client{user="hello"} 32577898872 (30.34 GB)
telemt_user_octets_to_client{user="hello"} 224081985973 (208.69 GB)
telemt_user_msgs_from_client{user="hello"} 2449
telemt_user_msgs_to_client{user="hello"} 3730
telemt_user_unique_ips_current{user="hello"} 480
telemt_user_unique_ips_recent_window{user="hello"} 180
```

## psb.hosting

```
telemt 3.3.24

telemt_uptime_seconds 59399.3 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3688428
telemt_connections_bad_total 330393
telemt_connections_current 3681
telemt_connections_me_current 3681
telemt_handshake_timeouts_total 85608
telemt_upstream_connect_attempt_total 11240
telemt_upstream_connect_success_total 11034
telemt_upstream_connect_fail_total 206
telemt_upstream_connect_attempts_per_request{bucket="1"} 11240
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6245
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4728
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 206
telemt_me_keepalive_timeout_total 46
telemt_me_reconnect_attempts_total 11127
telemt_me_reconnect_success_total 6876
telemt_me_reader_eof_total 7353
telemt_me_idle_close_by_peer_total 7353
telemt_me_route_drop_no_conn_total 1657344
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3018858
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 12468
telemt_desync_full_logged_total 4175
telemt_desync_suppressed_total 8293
telemt_desync_frames_bucket_total{bucket="1_2"} 2381
telemt_desync_frames_bucket_total{bucket="3_10"} 4828
telemt_desync_frames_bucket_total{bucket="gt_10"} 5259
telemt_pool_swap_total 53
telemt_pool_stale_pick_total 7
telemt_me_writer_close_signal_drop_total 57
telemt_me_writer_removed_unexpected_total 7092
telemt_me_refill_failed_total 131
telemt_me_writer_restored_same_endpoint_total 6821
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 13
telemt_me_async_recovery_trigger_total 631
telemt_me_writer_removed_unexpected_minus_restored_total 216
telemt_user_connections_total{user="hello"} 3018579
telemt_user_connections_current{user="hello"} 3681
telemt_user_octets_from_client{user="hello"} 45679627022 (42.54 GB)
telemt_user_octets_to_client{user="hello"} 1146620006190 (1.04 TB)
telemt_user_msgs_from_client{user="hello"} 3634
telemt_user_msgs_to_client{user="hello"} 2851
telemt_user_unique_ips_current{user="hello"} 1309
telemt_user_unique_ips_recent_window{user="hello"} 497
```

## koara.io

```
telemt 3.3.24

telemt_uptime_seconds 59377.7 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3344494
telemt_connections_bad_total 492445
telemt_connections_current 2827
telemt_connections_me_current 2827
telemt_handshake_timeouts_total 52246
telemt_upstream_connect_attempt_total 9612
telemt_upstream_connect_success_total 9547
telemt_upstream_connect_fail_total 65
telemt_upstream_connect_attempts_per_request{bucket="1"} 9612
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4846
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4684
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 17
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 65
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 7558
telemt_me_reconnect_success_total 6617
telemt_me_reader_eof_total 6968
telemt_me_idle_close_by_peer_total 6967
telemt_me_route_drop_no_conn_total 2038950
telemt_me_route_drop_channel_closed_total 183
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2349420
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 8671
telemt_desync_full_logged_total 2676
telemt_desync_suppressed_total 5995
telemt_desync_frames_bucket_total{bucket="1_2"} 2158
telemt_desync_frames_bucket_total{bucket="3_10"} 3294
telemt_desync_frames_bucket_total{bucket="gt_10"} 3219
telemt_pool_swap_total 59
telemt_me_writer_close_signal_drop_total 75
telemt_me_writer_removed_unexpected_total 6688
telemt_me_refill_failed_total 28
telemt_me_writer_restored_same_endpoint_total 6616
telemt_me_writer_restored_fallback_total 1
telemt_me_async_recovery_trigger_total 5604
telemt_me_writer_removed_unexpected_minus_restored_total 71
telemt_user_connections_total{user="hello"} 2344464
telemt_user_connections_current{user="hello"} 2827
telemt_user_octets_from_client{user="hello"} 35507112968 (33.07 GB)
telemt_user_octets_to_client{user="hello"} 950979700036 (885.67 GB)
telemt_user_unique_ips_current{user="hello"} 996
telemt_user_unique_ips_recent_window{user="hello"} 353
```

## landvps.ru

```
telemt 3.3.24

telemt_uptime_seconds 59365.2 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3040962
telemt_connections_bad_total 226580
telemt_connections_current 2811
telemt_connections_me_current 2811
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_demotions_total 1790
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 41849
telemt_upstream_connect_attempt_total 63584
telemt_upstream_connect_success_total 59022
telemt_upstream_connect_fail_total 4562
telemt_upstream_connect_attempts_per_request{bucket="1"} 63584
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 49801
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8645
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 25
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 551
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 4562
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 9886
telemt_me_reconnect_success_total 6950
telemt_me_reader_eof_total 7257
telemt_me_idle_close_by_peer_total 7256
telemt_me_route_drop_no_conn_total 2069989
telemt_me_route_drop_channel_closed_total 69
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2472022
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 17
telemt_me_endpoint_quarantine_total 2
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 9433
telemt_desync_full_logged_total 3004
telemt_desync_suppressed_total 6429
telemt_desync_frames_bucket_total{bucket="1_2"} 2255
telemt_desync_frames_bucket_total{bucket="3_10"} 3479
telemt_desync_frames_bucket_total{bucket="gt_10"} 3699
telemt_pool_swap_total 46
telemt_me_writer_close_signal_drop_total 541
telemt_me_writer_removed_unexpected_total 7636
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 6946
telemt_me_writer_restored_fallback_total 4
telemt_me_async_recovery_trigger_total 402
telemt_me_writer_removed_unexpected_minus_restored_total 686
telemt_user_connections_total{user="hello"} 2519202
telemt_user_connections_current{user="hello"} 2811
telemt_user_octets_from_client{user="hello"} 39393502449 (36.69 GB)
telemt_user_octets_to_client{user="hello"} 756016190923 (704.09 GB)
telemt_user_msgs_from_client{user="hello"} 254085
telemt_user_msgs_to_client{user="hello"} 1776413
telemt_user_unique_ips_current{user="hello"} 959
telemt_user_unique_ips_recent_window{user="hello"} 379
```

## rdp-onedash.ru

```
telemt 3.3.23

telemt_uptime_seconds 113088.3 (31h 24m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6794214
telemt_connections_bad_total 1190996
telemt_connections_current 3195
telemt_connections_me_current 3195
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_demotions_total 4345
telemt_relay_adaptive_hard_promotions_total 27
telemt_handshake_timeouts_total 120593
telemt_upstream_connect_attempt_total 129615
telemt_upstream_connect_success_total 96313
telemt_upstream_connect_fail_total 33302
telemt_upstream_connect_attempts_per_request{bucket="1"} 129615
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 81379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13497
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1437
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 33302
telemt_me_keepalive_failed_total 2
telemt_me_keepalive_timeout_total 118
telemt_me_reconnect_attempts_total 80055
telemt_me_reconnect_success_total 14375
telemt_me_reader_eof_total 15465
telemt_me_idle_close_by_peer_total 15451
telemt_me_route_drop_no_conn_total 2920533
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4793458
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
telemt_desync_total 20833
telemt_desync_full_logged_total 6626
telemt_desync_suppressed_total 14207
telemt_desync_frames_bucket_total{bucket="1_2"} 3698
telemt_desync_frames_bucket_total{bucket="3_10"} 8620
telemt_desync_frames_bucket_total{bucket="gt_10"} 8515
telemt_pool_swap_total 101
telemt_me_writer_removed_unexpected_total 14702
telemt_me_refill_failed_total 2047
telemt_me_writer_restored_same_endpoint_total 14350
telemt_me_writer_restored_fallback_total 25
telemt_me_no_writer_failfast_total 1489
telemt_me_async_recovery_trigger_total 7328
telemt_me_writer_removed_unexpected_minus_restored_total 327
telemt_user_connections_total{user="hello"} 4868513
telemt_user_connections_current{user="hello"} 3195
telemt_user_octets_from_client{user="hello"} 77017683612 (71.73 GB)
telemt_user_octets_to_client{user="hello"} 1923113332536 (1.75 TB)
telemt_user_msgs_from_client{user="hello"} 754082
telemt_user_msgs_to_client{user="hello"} 3090177
telemt_user_unique_ips_current{user="hello"} 1094
telemt_user_unique_ips_recent_window{user="hello"} 408
```

## hostvds.com

```
telemt 3.3.24

telemt_uptime_seconds 59328.4 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1510766
telemt_connections_bad_total 103123
telemt_connections_current 946
telemt_connections_me_current 946
telemt_relay_adaptive_promotions_total 29
telemt_relay_adaptive_hard_promotions_total 29
telemt_handshake_timeouts_total 14316
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
telemt_me_route_drop_no_conn_total 473482
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
telemt_desync_total 1539
telemt_desync_full_logged_total 575
telemt_desync_suppressed_total 964
telemt_desync_frames_bucket_total{bucket="1_2"} 234
telemt_desync_frames_bucket_total{bucket="3_10"} 688
telemt_desync_frames_bucket_total{bucket="gt_10"} 617
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
telemt_user_connections_total{user="hello"} 1333259
telemt_user_connections_current{user="hello"} 946
telemt_user_octets_from_client{user="hello"} 9015347763 (8.40 GB)
telemt_user_octets_to_client{user="hello"} 146629836494 (136.56 GB)
telemt_user_msgs_from_client{user="hello"} 11096
telemt_user_msgs_to_client{user="hello"} 16837
telemt_user_unique_ips_current{user="hello"} 231
telemt_user_unique_ips_recent_window{user="hello"} 223
```

## 4vps.su

```
telemt 3.3.24

telemt_uptime_seconds 59329.8 (16h 28m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2401881
telemt_connections_bad_total 153698
telemt_connections_current 2689
telemt_connections_me_current 2689
telemt_handshake_timeouts_total 44138
telemt_upstream_connect_attempt_total 10632
telemt_upstream_connect_success_total 10566
telemt_upstream_connect_fail_total 66
telemt_upstream_connect_attempts_per_request{bucket="1"} 10632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5698
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4831
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 66
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 7677
telemt_me_reconnect_success_total 7628
telemt_me_reader_eof_total 8060
telemt_me_idle_close_by_peer_total 8060
telemt_me_route_drop_no_conn_total 846503
telemt_me_route_drop_channel_closed_total 6
telemt_me_route_drop_queue_full_total 8
telemt_me_route_drop_queue_full_profile_total{profile="high"} 8
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2017171
telemt_me_writer_pick_total{mode="p2c",result="full"} 10
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 22
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 10274
telemt_desync_full_logged_total 3325
telemt_desync_suppressed_total 6949
telemt_desync_frames_bucket_total{bucket="1_2"} 1999
telemt_desync_frames_bucket_total{bucket="3_10"} 3624
telemt_desync_frames_bucket_total{bucket="gt_10"} 4651
telemt_pool_swap_total 60
telemt_me_writer_close_signal_drop_total 42
telemt_me_writer_removed_unexpected_total 7734
telemt_me_writer_restored_same_endpoint_total 7611
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 140
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 2015871
telemt_user_connections_current{user="hello"} 2689
telemt_user_octets_from_client{user="hello"} 42732060696 (39.80 GB)
telemt_user_octets_to_client{user="hello"} 1065199204036 (992.04 GB)
telemt_user_unique_ips_current{user="hello"} 942
telemt_user_unique_ips_recent_window{user="hello"} 308
```