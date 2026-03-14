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

# Server Metrics 2026-03-14 05:41:12 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.15

telemt_uptime_seconds 166071.9 (46h 7m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 640176
telemt_connections_bad_total 32298
telemt_handshake_timeouts_total 12991
telemt_upstream_connect_attempt_total 42388
telemt_upstream_connect_success_total 42172
telemt_upstream_connect_fail_total 216
telemt_upstream_connect_attempts_per_request{bucket="1"} 42388
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19253
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 22768
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 151
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 216
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 5572
telemt_me_reconnect_attempts_total 38196
telemt_me_reconnect_success_total 33508
telemt_me_reader_eof_total 35826
telemt_me_idle_close_by_peer_total 35825
telemt_me_route_drop_no_conn_total 209097
telemt_me_route_drop_channel_closed_total 30
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 542613
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 20
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1929
telemt_desync_full_logged_total 658
telemt_desync_suppressed_total 1271
telemt_desync_frames_bucket_total{bucket="1_2"} 417
telemt_desync_frames_bucket_total{bucket="3_10"} 704
telemt_desync_frames_bucket_total{bucket="gt_10"} 808
telemt_pool_swap_total 153
telemt_me_writer_removed_unexpected_total 34017
telemt_me_refill_failed_total 140
telemt_me_writer_restored_same_endpoint_total 33488
telemt_me_writer_restored_fallback_total 20
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 509
telemt_user_connections_total{user="hello"} 542498
telemt_user_connections_current{user="hello"} 302
telemt_user_octets_from_client{user="hello"} 15952119246 (14.86 GB)
telemt_user_octets_to_client{user="hello"} 262852575060 (244.80 GB)
telemt_user_msgs_from_client{user="hello"} 2142
telemt_user_msgs_to_client{user="hello"} 2404
telemt_user_unique_ips_current{user="hello"} 91
telemt_user_unique_ips_recent_window{user="hello"} 29
```

## psb.hosting

```
telemt 3.3.15

telemt_uptime_seconds 165965.6 (46h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 323243
telemt_connections_bad_total 2288
telemt_handshake_timeouts_total 2346
telemt_upstream_connect_attempt_total 148574
telemt_upstream_connect_success_total 147351
telemt_upstream_connect_fail_total 1223
telemt_upstream_connect_attempts_per_request{bucket="1"} 148574
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 109309
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35624
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2418
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1223
telemt_me_keepalive_timeout_total 3900
telemt_me_reconnect_attempts_total 172578
telemt_me_reconnect_success_total 35765
telemt_me_reader_eof_total 40986
telemt_me_idle_close_by_peer_total 40986
telemt_me_route_drop_no_conn_total 104326
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 203089
telemt_me_writer_pick_total{mode="p2c",result="full"} 7
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 42
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 33
telemt_desync_full_logged_total 11
telemt_desync_suppressed_total 22
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 12
telemt_desync_frames_bucket_total{bucket="gt_10"} 19
telemt_pool_swap_total 33
telemt_me_writer_removed_unexpected_total 40376
telemt_me_refill_failed_total 4269
telemt_me_writer_restored_same_endpoint_total 35748
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 30
telemt_me_writer_removed_unexpected_minus_restored_total 4611
telemt_user_connections_total{user="hello"} 306197
telemt_user_connections_current{user="hello"} 113
telemt_user_octets_from_client{user="hello"} 3180649255 (2.96 GB)
telemt_user_octets_to_client{user="hello"} 99688923547 (92.84 GB)
telemt_user_msgs_from_client{user="hello"} 1686033
telemt_user_msgs_to_client{user="hello"} 9368110
telemt_user_unique_ips_current{user="hello"} 47
telemt_user_unique_ips_recent_window{user="hello"} 20
```

## koara.io

```
telemt 3.3.15

telemt_uptime_seconds 165929.5 (46h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 375822
telemt_connections_bad_total 2964
telemt_handshake_timeouts_total 34918
telemt_upstream_connect_attempt_total 43959
telemt_upstream_connect_success_total 43950
telemt_upstream_connect_fail_total 9
telemt_upstream_connect_attempts_per_request{bucket="1"} 43959
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20067
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 23815
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 7
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 9
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3411
telemt_me_reconnect_attempts_total 36917
telemt_me_reconnect_success_total 35633
telemt_me_reader_eof_total 38317
telemt_me_idle_close_by_peer_total 38317
telemt_me_route_drop_no_conn_total 135315
telemt_me_route_drop_channel_closed_total 20
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 324905
telemt_me_writer_pick_total{mode="p2c",result="full"} 6
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 112
telemt_desync_full_logged_total 52
telemt_desync_suppressed_total 60
telemt_desync_frames_bucket_total{bucket="1_2"} 12
telemt_desync_frames_bucket_total{bucket="3_10"} 38
telemt_desync_frames_bucket_total{bucket="gt_10"} 62
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 36065
telemt_me_refill_failed_total 33
telemt_me_writer_restored_same_endpoint_total 35612
telemt_me_writer_restored_fallback_total 21
telemt_me_async_recovery_trigger_total 47
telemt_me_writer_removed_unexpected_minus_restored_total 432
telemt_user_connections_total{user="hello"} 324679
telemt_user_connections_current{user="hello"} 114
telemt_user_octets_from_client{user="hello"} 13040654680 (12.15 GB)
telemt_user_octets_to_client{user="hello"} 129401694872 (120.51 GB)
telemt_user_unique_ips_current{user="hello"} 50
telemt_user_unique_ips_recent_window{user="hello"} 16
```

## landvps.ru

```
telemt 3.3.15

telemt_uptime_seconds 165904.9 (46h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 477671
telemt_connections_bad_total 15653
telemt_handshake_timeouts_total 4477
telemt_upstream_connect_attempt_total 73996
telemt_upstream_connect_success_total 63449
telemt_upstream_connect_fail_total 10547
telemt_upstream_connect_attempts_per_request{bucket="1"} 73996
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37641
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25464
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 9
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 335
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 10547
telemt_me_keepalive_timeout_total 5314
telemt_me_reconnect_attempts_total 142195
telemt_me_reconnect_success_total 36140
telemt_me_reader_eof_total 40606
telemt_me_idle_close_by_peer_total 40598
telemt_me_route_drop_no_conn_total 171618
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 405889
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 19
telemt_me_endpoint_quarantine_total 19
telemt_me_hardswap_pending_ttl_expired_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 1726
telemt_desync_full_logged_total 509
telemt_desync_suppressed_total 1217
telemt_desync_frames_bucket_total{bucket="1_2"} 408
telemt_desync_frames_bucket_total{bucket="3_10"} 652
telemt_desync_frames_bucket_total{bucket="gt_10"} 666
telemt_pool_swap_total 47
telemt_me_writer_removed_unexpected_total 39866
telemt_me_refill_failed_total 3307
telemt_me_writer_restored_same_endpoint_total 36130
telemt_me_writer_restored_fallback_total 10
telemt_me_async_recovery_trigger_total 20496
telemt_me_writer_removed_unexpected_minus_restored_total 3726
telemt_user_connections_total{user="hello"} 424730
telemt_user_connections_current{user="hello"} 153
telemt_user_octets_from_client{user="hello"} 9239855923 (8.61 GB)
telemt_user_octets_to_client{user="hello"} 167882735172 (156.35 GB)
telemt_user_msgs_from_client{user="hello"} 459818
telemt_user_msgs_to_client{user="hello"} 871707
telemt_user_unique_ips_current{user="hello"} 46
telemt_user_unique_ips_recent_window{user="hello"} 14
```

## rdp-onedash.ru

```
telemt 3.3.15

telemt_uptime_seconds 116076.3 (32h 14m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 190113
telemt_connections_bad_total 28215
telemt_handshake_timeouts_total 1659
telemt_upstream_connect_attempt_total 41430
telemt_upstream_connect_success_total 41044
telemt_upstream_connect_fail_total 386
telemt_upstream_connect_attempts_per_request{bucket="1"} 41430
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20560
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20349
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 135
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 386
telemt_me_keepalive_timeout_total 2416
telemt_me_reconnect_attempts_total 43819
telemt_me_reconnect_success_total 30394
telemt_me_reader_eof_total 32536
telemt_me_idle_close_by_peer_total 32536
telemt_me_route_drop_no_conn_total 56135
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 150159
telemt_me_writer_pick_total{mode="p2c",result="full"} 8
telemt_me_writer_pick_total{mode="p2c",result="closed"} 18
telemt_me_endpoint_quarantine_total 16
telemt_me_hardswap_pending_ttl_expired_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 623
telemt_desync_full_logged_total 147
telemt_desync_suppressed_total 476
telemt_desync_frames_bucket_total{bucket="1_2"} 99
telemt_desync_frames_bucket_total{bucket="3_10"} 306
telemt_desync_frames_bucket_total{bucket="gt_10"} 218
telemt_pool_swap_total 88
telemt_me_writer_removed_unexpected_total 31088
telemt_me_refill_failed_total 416
telemt_me_writer_restored_same_endpoint_total 30376
telemt_me_writer_restored_fallback_total 18
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 694
telemt_user_connections_total{user="hello"} 154908
telemt_user_connections_current{user="hello"} 69
telemt_user_octets_from_client{user="hello"} 2296154021 (2.14 GB)
telemt_user_octets_to_client{user="hello"} 70128585691 (65.31 GB)
telemt_user_msgs_from_client{user="hello"} 50955
telemt_user_msgs_to_client{user="hello"} 221508
telemt_user_unique_ips_current{user="hello"} 23
telemt_user_unique_ips_recent_window{user="hello"} 15
```

## hostvds.com

```
telemt 3.3.15

telemt_uptime_seconds 165860.9 (46h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 944150
telemt_connections_bad_total 32746
telemt_handshake_timeouts_total 25808
telemt_upstream_connect_attempt_total 34464
telemt_upstream_connect_success_total 34279
telemt_upstream_connect_fail_total 185
telemt_upstream_connect_attempts_per_request{bucket="1"} 34464
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16101
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18137
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 41
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 185
telemt_me_keepalive_timeout_total 4609
telemt_me_reconnect_attempts_total 30736
telemt_me_reconnect_success_total 26061
telemt_me_reader_eof_total 27976
telemt_me_idle_close_by_peer_total 27973
telemt_me_route_drop_no_conn_total 446392
telemt_me_route_drop_channel_closed_total 22
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 877743
telemt_me_writer_pick_total{mode="p2c",result="full"} 9
telemt_me_writer_pick_total{mode="p2c",result="closed"} 22
telemt_me_endpoint_quarantine_total 15
telemt_me_hardswap_pending_ttl_expired_total 3
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_desync_total 760
telemt_desync_full_logged_total 250
telemt_desync_suppressed_total 510
telemt_desync_frames_bucket_total{bucket="1_2"} 256
telemt_desync_frames_bucket_total{bucket="3_10"} 248
telemt_desync_frames_bucket_total{bucket="gt_10"} 256
telemt_pool_swap_total 157
telemt_me_writer_removed_unexpected_total 26538
telemt_me_refill_failed_total 141
telemt_me_writer_restored_same_endpoint_total 26054
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 34
telemt_me_writer_removed_unexpected_minus_restored_total 477
telemt_user_connections_total{user="hello"} 850402
telemt_user_connections_current{user="hello"} 412
telemt_user_octets_from_client{user="hello"} 14747570160 (13.73 GB)
telemt_user_octets_to_client{user="hello"} 434502977684 (404.66 GB)
telemt_user_unique_ips_current{user="hello"} 153
telemt_user_unique_ips_recent_window{user="hello"} 51
```