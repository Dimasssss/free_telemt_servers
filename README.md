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

# Server Metrics 2026-03-15 12:55:53 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.18

telemt_uptime_seconds 52884.6 (14h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 233188
telemt_connections_bad_total 2017
telemt_handshake_timeouts_total 4842
telemt_upstream_connect_attempt_total 13339
telemt_upstream_connect_success_total 13269
telemt_upstream_connect_fail_total 70
telemt_upstream_connect_attempts_per_request{bucket="1"} 13339
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5908
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7348
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 8
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 5
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 70
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 21
telemt_me_reconnect_attempts_total 14001
telemt_me_reconnect_success_total 10628
telemt_me_reader_eof_total 11358
telemt_me_idle_close_by_peer_total 11358
telemt_me_route_drop_no_conn_total 428729
telemt_me_route_drop_channel_closed_total 65
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 278500
telemt_me_writer_pick_total{mode="p2c",result="full"} 4
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 18
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1581
telemt_desync_full_logged_total 633
telemt_desync_suppressed_total 948
telemt_desync_frames_bucket_total{bucket="1_2"} 264
telemt_desync_frames_bucket_total{bucket="3_10"} 635
telemt_desync_frames_bucket_total{bucket="gt_10"} 682
telemt_pool_swap_total 46
telemt_me_writer_removed_unexpected_total 10842
telemt_me_refill_failed_total 104
telemt_me_writer_restored_same_endpoint_total 10597
telemt_me_writer_restored_fallback_total 31
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 214
telemt_user_connections_total{user="hello"} 217611
telemt_user_connections_current{user="hello"} 424
telemt_user_octets_from_client{user="hello"} 4482346652 (4.17 GB)
telemt_user_octets_to_client{user="hello"} 198397996576 (184.77 GB)
telemt_user_unique_ips_current{user="hello"} 126
telemt_user_unique_ips_recent_window{user="hello"} 47
```

## psb.hosting

```
telemt 3.3.18

telemt_uptime_seconds 52891.5 (14h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 83972
telemt_connections_bad_total 2709
telemt_handshake_timeouts_total 7162
telemt_upstream_connect_attempt_total 14562
telemt_upstream_connect_success_total 14562
telemt_upstream_connect_attempts_per_request{bucket="1"} 14562
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6235
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 119
telemt_me_keepalive_timeout_total 1
telemt_me_reconnect_attempts_total 14231
telemt_me_reconnect_success_total 11890
telemt_me_reader_eof_total 12729
telemt_me_idle_close_by_peer_total 12729
telemt_me_route_drop_no_conn_total 36458
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 71497
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 14
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 12095
telemt_me_refill_failed_total 71
telemt_me_writer_restored_same_endpoint_total 11874
telemt_me_writer_restored_fallback_total 16
telemt_me_async_recovery_trigger_total 32
telemt_me_writer_removed_unexpected_minus_restored_total 205
telemt_user_connections_total{user="hello"} 71494
telemt_user_connections_current{user="hello"} 227
telemt_user_octets_from_client{user="hello"} 1445679876 (1.35 GB)
telemt_user_octets_to_client{user="hello"} 34923930272 (32.53 GB)
telemt_user_unique_ips_current{user="hello"} 52
telemt_user_unique_ips_recent_window{user="hello"} 18
```

## koara.io

```
telemt 3.3.18

telemt_uptime_seconds 52883.5 (14h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 86813
telemt_connections_bad_total 1045
telemt_handshake_timeouts_total 2670
telemt_upstream_connect_attempt_total 15374
telemt_upstream_connect_success_total 15366
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 15374
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 6678
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 8658
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 30
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_reconnect_attempts_total 14843
telemt_me_reconnect_success_total 12695
telemt_me_reader_eof_total 13590
telemt_me_idle_close_by_peer_total 13590
telemt_me_route_drop_no_conn_total 33494
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 79302
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 12
telemt_me_endpoint_quarantine_total 12
telemt_me_hardswap_pending_ttl_expired_total 2
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 54
telemt_desync_full_logged_total 20
telemt_desync_suppressed_total 34
telemt_desync_frames_bucket_total{bucket="1_2"} 4
telemt_desync_frames_bucket_total{bucket="3_10"} 26
telemt_desync_frames_bucket_total{bucket="gt_10"} 24
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 12884
telemt_me_refill_failed_total 65
telemt_me_writer_restored_same_endpoint_total 12687
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 189
telemt_user_connections_total{user="hello"} 79216
telemt_user_connections_current{user="hello"} 155
telemt_user_octets_from_client{user="hello"} 9626012704 (8.96 GB)
telemt_user_octets_to_client{user="hello"} 49159097108 (45.78 GB)
telemt_user_unique_ips_current{user="hello"} 62
telemt_user_unique_ips_recent_window{user="hello"} 25
```

## landvps.ru

```
telemt 3.3.18

telemt_uptime_seconds 52883.1 (14h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 118743
telemt_connections_bad_total 397
telemt_handshake_timeouts_total 765
telemt_upstream_connect_attempt_total 12378
telemt_upstream_connect_success_total 12377
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 12378
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5933
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6403
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_keepalive_timeout_total 8
telemt_me_reconnect_attempts_total 9794
telemt_me_reconnect_success_total 9737
telemt_me_reader_eof_total 10393
telemt_me_idle_close_by_peer_total 10393
telemt_me_route_drop_no_conn_total 47024
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 108239
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 19
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 294
telemt_desync_full_logged_total 90
telemt_desync_suppressed_total 204
telemt_desync_frames_bucket_total{bucket="1_2"} 74
telemt_desync_frames_bucket_total{bucket="3_10"} 119
telemt_desync_frames_bucket_total{bucket="gt_10"} 101
telemt_pool_swap_total 51
telemt_me_writer_removed_unexpected_total 9848
telemt_me_writer_restored_same_endpoint_total 9726
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 25
telemt_me_writer_removed_unexpected_minus_restored_total 111
telemt_user_connections_total{user="hello"} 108159
telemt_user_connections_current{user="hello"} 187
telemt_user_octets_from_client{user="hello"} 1918079588 (1.79 GB)
telemt_user_octets_to_client{user="hello"} 57487787792 (53.54 GB)
telemt_user_unique_ips_current{user="hello"} 66
telemt_user_unique_ips_recent_window{user="hello"} 27
```

## rdp-onedash.ru

```
telemt 3.3.18

telemt_uptime_seconds 27954.7 (7h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 65597
telemt_connections_bad_total 17721
telemt_handshake_timeouts_total 875
telemt_upstream_connect_attempt_total 8876
telemt_upstream_connect_success_total 8814
telemt_upstream_connect_fail_total 62
telemt_upstream_connect_attempts_per_request{bucket="1"} 8876
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3965
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4814
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 62
telemt_me_reconnect_attempts_total 101655
telemt_me_reconnect_success_total 7235
telemt_me_reader_eof_total 7547
telemt_me_idle_close_by_peer_total 7547
telemt_me_route_drop_no_conn_total 22517
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 45527
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 21
telemt_me_endpoint_quarantine_total 11
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 116
telemt_desync_full_logged_total 25
telemt_desync_suppressed_total 91
telemt_desync_frames_bucket_total{bucket="1_2"} 18
telemt_desync_frames_bucket_total{bucket="3_10"} 47
telemt_desync_frames_bucket_total{bucket="gt_10"} 51
telemt_pool_swap_total 19
telemt_me_writer_removed_unexpected_total 7230
telemt_me_refill_failed_total 3033
telemt_me_writer_restored_same_endpoint_total 7131
telemt_me_writer_restored_fallback_total 104
telemt_me_async_recovery_trigger_total 2255
telemt_user_connections_total{user="hello"} 45662
telemt_user_connections_current{user="hello"} 88
telemt_user_octets_from_client{user="hello"} 676659685 (645.31 MB)
telemt_user_octets_to_client{user="hello"} 17901756743 (16.67 GB)
telemt_user_msgs_from_client{user="hello"} 2259
telemt_user_msgs_to_client{user="hello"} 12105
telemt_user_unique_ips_current{user="hello"} 35
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## hostvds.com

```
telemt 3.3.18

telemt_uptime_seconds 52882.5 (14h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 307929
telemt_connections_bad_total 47768
telemt_handshake_timeouts_total 2495
telemt_upstream_connect_attempt_total 11232
telemt_upstream_connect_success_total 11163
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 11232
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5593
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5567
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 8569
telemt_me_reconnect_success_total 8511
telemt_me_reader_eof_total 9053
telemt_me_idle_close_by_peer_total 9053
telemt_me_route_drop_no_conn_total 137327
telemt_me_route_drop_channel_closed_total 31
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 248589
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 18
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 203
telemt_desync_full_logged_total 67
telemt_desync_suppressed_total 136
telemt_desync_frames_bucket_total{bucket="1_2"} 95
telemt_desync_frames_bucket_total{bucket="3_10"} 68
telemt_desync_frames_bucket_total{bucket="gt_10"} 40
telemt_pool_swap_total 50
telemt_me_writer_removed_unexpected_total 8587
telemt_me_writer_restored_same_endpoint_total 8484
telemt_me_writer_restored_fallback_total 27
telemt_me_async_recovery_trigger_total 40
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 246950
telemt_user_connections_current{user="hello"} 570
telemt_user_octets_from_client{user="hello"} 5113876756 (4.76 GB)
telemt_user_octets_to_client{user="hello"} 117210335364 (109.16 GB)
telemt_user_unique_ips_current{user="hello"} 224
telemt_user_unique_ips_recent_window{user="hello"} 61
```