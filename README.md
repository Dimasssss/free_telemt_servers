# Информация

Покупаю сервера у разных хостингов для запуска прокси для Telegram

Для прокси используется https://github.com/telemt/telemt
[Конфиг](https://github.com/Dimasssss/free_telemt_servers/blob/main/config.toml) используемый на всех серверах.

### **Принимаю донаты криптой для добавления и продления серверов:**
- TON (Можно отправлять TON и USDT в сети TON):
```
UQAyIvWts4-gC0b5ouoy_JNDfBEe337c7oOBqpGXFB8fJUzB
```
### **Спасибо:**
- Ivan Morozov - 20$

_Можете писать свой ник в коментарии к переводу_

### [Итог по хостингам](Reviews.md)

---

## NKtelecom
- Локация: Netherlands - Amsterdam
- Тариф: AMS-CLOUD-60
- Краткое описание тарифа: 4 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 4.99$
- Оплачен до: 26 апреля
- Ссылка:
```bash
tg://proxy?server=s1.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## psb.hosting (2 сервера)
- Локация: Finland
- Тариф: FI-200
- Краткое описание тарифа: 2 vCore, 4 Gb ram, 1 Gbit/s
- Цена в месяц: 12$
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

## rdp-onedash.ru (2 сервера)
- Локация: Нидерланды
- Тариф: Mini
- Краткое описание тарифа: 2 vCore, 2 Gb ram, 1 Gbit/s
- Цена в месяц: 844 RUB
- Ссылка:
```bash
tg://proxy?server=s5.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## hostvds.com
- Локация: Франция, Париж
- Тариф: Highload-2
- Краткое описание тарифа: 2 vCore, 8 Gb ram, 10 Gbit/s
- Цена в месяц: €12.57
- Ссылка:
```bash
tg://proxy?server=s6.dimasssss.space&port=443&secret=eebe3007e927acd147dde12bee8b1a7c9364726976652e676f6f676c652e636f6d
```

-----

## 4vps.su (2 сервера)
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

# Server Metrics 2026-03-22 07:22:21 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 36944.4 (10h 15m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 768435
telemt_connections_bad_total 48853
telemt_connections_current 1561
telemt_connections_me_current 1561
telemt_handshake_timeouts_total 36389
telemt_upstream_connect_attempt_total 14988
telemt_upstream_connect_success_total 14987
telemt_upstream_connect_attempts_per_request{bucket="1"} 14987
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5190
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9752
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 422
telemt_me_reconnect_success_total 235
telemt_me_reader_eof_total 232
telemt_me_idle_close_by_peer_total 232
telemt_me_route_drop_no_conn_total 301107
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 636616
telemt_me_endpoint_quarantine_total 264
telemt_me_single_endpoint_shadow_rotate_total 300
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 7
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 16
telemt_desync_total 5117
telemt_desync_full_logged_total 1447
telemt_desync_suppressed_total 3670
telemt_desync_frames_bucket_total{bucket="1_2"} 1645
telemt_desync_frames_bucket_total{bucket="3_10"} 1923
telemt_desync_frames_bucket_total{bucket="gt_10"} 1549
telemt_pool_swap_total 40
telemt_pool_force_close_total 1079
telemt_me_writer_close_signal_drop_total 112
telemt_me_draining_writers_reap_progress_total 13559
telemt_me_writer_removed_unexpected_total 229
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 935
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12839
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1064
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12480
telemt_me_writer_teardown_success_total{mode="normal"} 13774
telemt_me_writer_teardown_noop_total 13560
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 26148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26948
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 27219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27323
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27334
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27334
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.994389
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27334
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 112
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 215
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 635437
telemt_user_connections_current{user="hello"} 1561
telemt_user_octets_from_client{user="hello"} 8727964080 (8.13 GB)
telemt_user_octets_to_client{user="hello"} 217833806496 (202.87 GB)
telemt_user_unique_ips_current{user="hello"} 597
telemt_user_unique_ips_recent_window{user="hello"} 227
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 50311.9 (13h 58m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1245980
telemt_connections_bad_total 120837
telemt_connections_current 1603
telemt_connections_me_current 1603
telemt_handshake_timeouts_total 39031
telemt_upstream_connect_attempt_total 26433
telemt_upstream_connect_success_total 26043
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 26382
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13249
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12737
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 57
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1967
telemt_me_reconnect_success_total 794
telemt_me_reader_eof_total 690
telemt_me_idle_close_by_peer_total 690
telemt_me_route_drop_no_conn_total 473051
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 938792
telemt_me_endpoint_quarantine_total 460
telemt_me_single_endpoint_outage_enter_total 23
telemt_me_single_endpoint_outage_exit_total 23
telemt_me_single_endpoint_outage_reconnect_attempt_total 23
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 23
telemt_me_single_endpoint_shadow_rotate_total 402
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 25
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_desync_total 4070
telemt_desync_full_logged_total 2375
telemt_desync_suppressed_total 1695
telemt_desync_frames_bucket_total{bucket="1_2"} 863
telemt_desync_frames_bucket_total{bucket="3_10"} 1572
telemt_desync_frames_bucket_total{bucket="gt_10"} 1635
telemt_pool_swap_total 53
telemt_pool_force_close_total 1420
telemt_me_writer_close_signal_drop_total 115
telemt_me_draining_writers_reap_progress_total 20603
telemt_me_writer_removed_unexpected_total 663
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1838
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19414
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1352
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19183
telemt_me_writer_teardown_success_total{mode="normal"} 21252
telemt_me_writer_teardown_noop_total 20603
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 41039
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41538
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41855
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.332301
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41855
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 115
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 602
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 16
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 940536
telemt_user_connections_current{user="hello"} 1603
telemt_user_octets_from_client{user="hello"} 14955693686 (13.93 GB)
telemt_user_octets_to_client{user="hello"} 343865638915 (320.25 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 999
telemt_user_unique_ips_recent_window{user="hello"} 467
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 125170.5 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9019683
telemt_connections_bad_total 829877
telemt_connections_current 4720
telemt_connections_me_current 4720
telemt_handshake_timeouts_total 281580
telemt_upstream_connect_attempt_total 46227
telemt_upstream_connect_success_total 46148
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 46156
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20843
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25111
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1753
telemt_me_reconnect_success_total 915
telemt_me_reader_eof_total 918
telemt_me_idle_close_by_peer_total 918
telemt_me_route_drop_no_conn_total 4880021
telemt_me_route_drop_channel_closed_total 74
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7104523
telemt_me_endpoint_quarantine_total 789
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 940
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 19
telemt_desync_total 30836
telemt_desync_full_logged_total 10198
telemt_desync_suppressed_total 20638
telemt_desync_frames_bucket_total{bucket="1_2"} 6684
telemt_desync_frames_bucket_total{bucket="3_10"} 11978
telemt_desync_frames_bucket_total{bucket="gt_10"} 12174
telemt_pool_swap_total 135
telemt_pool_force_close_total 4457
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 42178
telemt_me_writer_removed_unexpected_total 882
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3500
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39060
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 269
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37721
telemt_me_writer_teardown_success_total{mode="normal"} 42560
telemt_me_writer_teardown_noop_total 42222
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77780
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79870
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80997
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82666
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83840
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84462
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84771
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84782
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84782
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 177.317331
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84782
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 816
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 7095250
telemt_user_connections_current{user="hello"} 4720
telemt_user_octets_from_client{user="hello"} 119745611808 (111.52 GB)
telemt_user_octets_to_client{user="hello"} 2428053421428 (2.21 TB)
telemt_user_unique_ips_current{user="hello"} 1953
telemt_user_unique_ips_recent_window{user="hello"} 631
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 125171.7 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7428935
telemt_connections_bad_total 654837
telemt_connections_current 4182
telemt_connections_me_current 4182
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 243614
telemt_upstream_connect_attempt_total 50267
telemt_upstream_connect_success_total 49861
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 50070
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24577
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24692
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2631
telemt_me_reconnect_success_total 990
telemt_me_reader_eof_total 956
telemt_me_idle_close_by_peer_total 956
telemt_me_route_drop_no_conn_total 2496495
telemt_me_route_drop_channel_closed_total 304
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5509134
telemt_me_endpoint_quarantine_total 789
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 962
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 34
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 45
telemt_me_writers_warm_current 29
telemt_desync_total 25377
telemt_desync_full_logged_total 8704
telemt_desync_suppressed_total 16673
telemt_desync_frames_bucket_total{bucket="1_2"} 6057
telemt_desync_frames_bucket_total{bucket="3_10"} 9856
telemt_desync_frames_bucket_total{bucket="gt_10"} 9464
telemt_pool_swap_total 136
telemt_pool_force_close_total 4060
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 420
telemt_me_draining_writers_reap_progress_total 40658
telemt_me_writer_removed_unexpected_total 933
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3370
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38150
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 236
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36598
telemt_me_writer_teardown_success_total{mode="normal"} 41520
telemt_me_writer_teardown_noop_total 40664
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78325
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 80148
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80844
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82184
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82184
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.969685
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82184
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 420
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 866
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 5430146
telemt_user_connections_current{user="hello"} 4182
telemt_user_octets_from_client{user="hello"} 154333573989 (143.73 GB)
telemt_user_octets_to_client{user="hello"} 2626442147227 (2.39 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1698
telemt_user_unique_ips_recent_window{user="hello"} 531
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 125136.6 (34h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7191756
telemt_connections_bad_total 592005
telemt_connections_current 3333
telemt_connections_me_current 3333
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 239794
telemt_upstream_connect_attempt_total 56831
telemt_upstream_connect_success_total 56168
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 56315
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27726
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26283
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 876
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1283
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2700
telemt_me_reconnect_success_total 1170
telemt_me_reader_eof_total 1085
telemt_me_idle_close_by_peer_total 1085
telemt_me_route_drop_no_conn_total 2900917
telemt_me_route_drop_channel_closed_total 172
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5368414
telemt_me_endpoint_quarantine_total 877
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 925
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 47
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 78
telemt_me_writers_warm_current 9
telemt_desync_total 25060
telemt_desync_full_logged_total 8543
telemt_desync_suppressed_total 16517
telemt_desync_frames_bucket_total{bucket="1_2"} 6086
telemt_desync_frames_bucket_total{bucket="3_10"} 9604
telemt_desync_frames_bucket_total{bucket="gt_10"} 9370
telemt_pool_swap_total 133
telemt_pool_force_close_total 3895
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 449
telemt_me_draining_writers_reap_progress_total 41553
telemt_me_writer_removed_unexpected_total 1096
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3673
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38990
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3637
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37658
telemt_me_writer_teardown_success_total{mode="normal"} 42663
telemt_me_writer_teardown_noop_total 41565
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 81038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83197
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84092
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84178
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84228
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.879028
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84228
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 449
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 1014
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 5362226
telemt_user_connections_current{user="hello"} 3333
telemt_user_octets_from_client{user="hello"} 142501563347 (132.71 GB)
telemt_user_octets_to_client{user="hello"} 2392683907271 (2.18 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1434
telemt_user_unique_ips_recent_window{user="hello"} 466
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 125190.3 (34h 46m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 23010233
telemt_connections_bad_total 1923154
telemt_connections_current 5557
telemt_connections_me_current 5557
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 679112
telemt_upstream_connect_attempt_total 238996
telemt_upstream_connect_success_total 219356
telemt_upstream_connect_fail_total 17680
telemt_upstream_connect_attempts_per_request{bucket="1"} 237036
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154307
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51536
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11036
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17680
telemt_me_keepalive_timeout_total 400
telemt_me_reconnect_attempts_total 66409
telemt_me_reconnect_success_total 2632
telemt_me_reader_eof_total 1657
telemt_me_idle_close_by_peer_total 1655
telemt_me_route_drop_no_conn_total 43986235
telemt_me_route_drop_channel_closed_total 138
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18539993
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 973
telemt_me_single_endpoint_outage_enter_total 156
telemt_me_single_endpoint_outage_exit_total 156
telemt_me_single_endpoint_outage_reconnect_attempt_total 325
telemt_me_single_endpoint_outage_reconnect_success_total 82
telemt_me_single_endpoint_quarantine_bypass_total 325
telemt_me_single_endpoint_shadow_rotate_total 978
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 70
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 31
telemt_desync_total 35919
telemt_desync_full_logged_total 10730
telemt_desync_suppressed_total 25189
telemt_desync_frames_bucket_total{bucket="1_2"} 7965
telemt_desync_frames_bucket_total{bucket="3_10"} 15917
telemt_desync_frames_bucket_total{bucket="gt_10"} 12037
telemt_pool_swap_total 129
telemt_pool_force_close_total 4090
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 936
telemt_me_draining_writers_reap_progress_total 39082
telemt_me_writer_removed_unexpected_total 2435
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5272
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35976
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3507
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 583
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34992
telemt_me_writer_teardown_success_total{mode="normal"} 41248
telemt_me_writer_teardown_noop_total 39114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72787
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 77031
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79867
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80226
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80318
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80346
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80349
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80357
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80362
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 280.428355
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80362
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 936
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1792
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 18704635
telemt_user_connections_current{user="hello"} 5558
telemt_user_octets_from_client{user="hello"} 272480009439 (253.77 GB)
telemt_user_octets_to_client{user="hello"} 1403937302038 (1.28 TB)
telemt_user_msgs_from_client{user="hello"} 500908
telemt_user_msgs_to_client{user="hello"} 1006528
telemt_user_unique_ips_current{user="hello"} 2056
telemt_user_unique_ips_recent_window{user="hello"} 1116
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 125142.4 (34h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6862766
telemt_connections_bad_total 631639
telemt_connections_current 3886
telemt_connections_me_current 3886
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 142179
telemt_upstream_connect_attempt_total 65266
telemt_upstream_connect_success_total 64522
telemt_upstream_connect_fail_total 638
telemt_upstream_connect_attempts_per_request{bucket="1"} 65160
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36932
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27224
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 638
telemt_me_reconnect_attempts_total 70006
telemt_me_reconnect_success_total 1924
telemt_me_reader_eof_total 1701
telemt_me_idle_close_by_peer_total 1700
telemt_me_route_drop_no_conn_total 2635494
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5368790
telemt_me_endpoint_quarantine_total 833
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 947
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 35
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 43
telemt_me_writers_warm_current 8
telemt_desync_total 26988
telemt_desync_full_logged_total 9400
telemt_desync_suppressed_total 17588
telemt_desync_frames_bucket_total{bucket="1_2"} 5399
telemt_desync_frames_bucket_total{bucket="3_10"} 10365
telemt_desync_frames_bucket_total{bucket="gt_10"} 11224
telemt_pool_swap_total 130
telemt_pool_force_close_total 3733
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 441
telemt_me_draining_writers_reap_progress_total 43798
telemt_me_writer_removed_unexpected_total 1732
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4384
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41183
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3318
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 415
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40065
telemt_me_writer_teardown_success_total{mode="normal"} 45567
telemt_me_writer_teardown_noop_total 43799
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89119
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89332
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89366
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89366
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.034678
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89366
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 441
telemt_me_refill_failed_total 4217
telemt_me_writer_restored_same_endpoint_total 1608
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5360001
telemt_user_connections_current{user="hello"} 3886
telemt_user_octets_from_client{user="hello"} 136915963672 (127.51 GB)
telemt_user_octets_to_client{user="hello"} 2242975458530 (2.04 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1642
telemt_user_unique_ips_recent_window{user="hello"} 572
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 61978.2 (17h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5113034
telemt_connections_bad_total 207227
telemt_connections_current 3402
telemt_connections_me_current 3402
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2027560
telemt_upstream_connect_attempt_total 34156
telemt_upstream_connect_success_total 33923
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 34149
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20326
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13510
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_reconnect_attempts_total 46214
telemt_me_reconnect_success_total 1074
telemt_me_reader_eof_total 765
telemt_me_idle_close_by_peer_total 765
telemt_me_route_drop_no_conn_total 1254994
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2548089
telemt_me_endpoint_quarantine_total 433
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 475
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 46
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 13541
telemt_desync_full_logged_total 4668
telemt_desync_suppressed_total 8873
telemt_desync_frames_bucket_total{bucket="1_2"} 2683
telemt_desync_frames_bucket_total{bucket="3_10"} 5180
telemt_desync_frames_bucket_total{bucket="gt_10"} 5678
telemt_pool_swap_total 67
telemt_pool_force_close_total 1969
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 177
telemt_me_draining_writers_reap_progress_total 22541
telemt_me_writer_removed_unexpected_total 835
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1894
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21504
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1744
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 225
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20572
telemt_me_writer_teardown_success_total{mode="normal"} 23398
telemt_me_writer_teardown_noop_total 22543
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45328
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45670
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45829
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45941
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45941
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.963891
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45941
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 177
telemt_me_refill_failed_total 2622
telemt_me_writer_restored_same_endpoint_total 958
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2549790
telemt_user_connections_current{user="hello"} 3402
telemt_user_octets_from_client{user="hello"} 65014479352 (60.55 GB)
telemt_user_octets_to_client{user="hello"} 1133017752994 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1445
telemt_user_unique_ips_recent_window{user="hello"} 553
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 42948.9 (11h 55m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 334186
telemt_connections_bad_total 2365
telemt_connections_current 757
telemt_connections_me_current 757
telemt_handshake_timeouts_total 7507
telemt_upstream_connect_attempt_total 20556
telemt_upstream_connect_success_total 20503
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 20552
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8610
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11763
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 130
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 894
telemt_me_reconnect_success_total 299
telemt_me_reader_eof_total 295
telemt_me_idle_close_by_peer_total 295
telemt_me_route_drop_no_conn_total 102418
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 303073
telemt_me_endpoint_quarantine_total 405
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 372
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_desync_total 1457
telemt_desync_full_logged_total 410
telemt_desync_suppressed_total 1047
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 560
telemt_desync_frames_bucket_total{bucket="gt_10"} 428
telemt_pool_swap_total 47
telemt_pool_force_close_total 1059
telemt_me_writer_close_signal_drop_total 39
telemt_me_draining_writers_reap_progress_total 18600
telemt_me_writer_removed_unexpected_total 282
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1215
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17680
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1057
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17541
telemt_me_writer_teardown_success_total{mode="normal"} 18895
telemt_me_writer_teardown_noop_total 18600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 37195
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 37455
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 37485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37495
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37495
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.487133
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37495
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 39
telemt_me_refill_failed_total 35
telemt_me_writer_restored_same_endpoint_total 253
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 27
telemt_user_connections_total{user="hello"} 302540
telemt_user_connections_current{user="hello"} 756
telemt_user_octets_from_client{user="hello"} 4944558892 (4.60 GB)
telemt_user_octets_to_client{user="hello"} 170564803516 (158.85 GB)
telemt_user_unique_ips_current{user="hello"} 286
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 125146.7 (34h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8391710
telemt_connections_bad_total 906157
telemt_connections_current 4035
telemt_connections_me_current 4035
telemt_handshake_timeouts_total 236419
telemt_upstream_connect_attempt_total 49046
telemt_upstream_connect_success_total 48866
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 49007
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24219
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24606
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_reconnect_attempts_total 1827
telemt_me_reconnect_success_total 990
telemt_me_reader_eof_total 967
telemt_me_idle_close_by_peer_total 967
telemt_me_route_drop_no_conn_total 2354583
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6230559
telemt_me_endpoint_quarantine_total 889
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 954
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 33
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 44
telemt_me_writers_warm_current 9
telemt_desync_total 24841
telemt_desync_full_logged_total 8155
telemt_desync_suppressed_total 16686
telemt_desync_frames_bucket_total{bucket="1_2"} 6151
telemt_desync_frames_bucket_total{bucket="3_10"} 9056
telemt_desync_frames_bucket_total{bucket="gt_10"} 9634
telemt_pool_swap_total 138
telemt_pool_force_close_total 3687
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 438
telemt_me_draining_writers_reap_progress_total 44263
telemt_me_writer_removed_unexpected_total 929
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3490
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41730
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40576
telemt_me_writer_teardown_success_total{mode="normal"} 45220
telemt_me_writer_teardown_noop_total 44265
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87988
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89187
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89394
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89485
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89485
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.387466
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89485
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 438
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 874
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6204391
telemt_user_connections_current{user="hello"} 4035
telemt_user_octets_from_client{user="hello"} 122820001656 (114.39 GB)
telemt_user_octets_to_client{user="hello"} 2912469677084 (2.65 TB)
telemt_user_unique_ips_current{user="hello"} 1583
telemt_user_unique_ips_recent_window{user="hello"} 625
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 125143.5 (34h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7323972
telemt_connections_bad_total 782712
telemt_connections_current 4085
telemt_connections_me_current 4085
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 195617
telemt_upstream_connect_attempt_total 64997
telemt_upstream_connect_success_total 64503
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 64933
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37052
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26310
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 623
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_reconnect_attempts_total 6015
telemt_me_reconnect_success_total 1383
telemt_me_reader_eof_total 1247
telemt_me_idle_close_by_peer_total 1247
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2423903
telemt_me_route_drop_channel_closed_total 201
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5574291
telemt_me_endpoint_quarantine_total 978
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 952
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 36
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 39
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 85
telemt_me_writers_warm_current 7
telemt_desync_total 23825
telemt_desync_full_logged_total 7915
telemt_desync_suppressed_total 15910
telemt_desync_frames_bucket_total{bucket="1_2"} 5896
telemt_desync_frames_bucket_total{bucket="3_10"} 8743
telemt_desync_frames_bucket_total{bucket="gt_10"} 9186
telemt_pool_swap_total 135
telemt_pool_force_close_total 3610
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 437
telemt_me_draining_writers_reap_progress_total 42824
telemt_me_writer_removed_unexpected_total 1262
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4064
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40083
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3378
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 232
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39214
telemt_me_writer_teardown_success_total{mode="normal"} 44147
telemt_me_writer_teardown_noop_total 42828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 85112
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 86277
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86937
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86975
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86975
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.486057
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86975
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 437
telemt_me_refill_failed_total 267
telemt_me_writer_restored_same_endpoint_total 1082
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 5576134
telemt_user_connections_current{user="hello"} 4085
telemt_user_octets_from_client{user="hello"} 103232057325 (96.14 GB)
telemt_user_octets_to_client{user="hello"} 2425155574380 (2.21 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1715
telemt_user_unique_ips_recent_window{user="hello"} 519
```