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

# Server Metrics 2026-03-22 07:11:56 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 36333.8 (10h 5m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 746438
telemt_connections_bad_total 47355
telemt_connections_current 1500
telemt_connections_me_current 1500
telemt_handshake_timeouts_total 35377
telemt_upstream_connect_attempt_total 14791
telemt_upstream_connect_success_total 14790
telemt_upstream_connect_attempts_per_request{bucket="1"} 14790
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5112
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 9633
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 34
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_reconnect_attempts_total 418
telemt_me_reconnect_success_total 232
telemt_me_reader_eof_total 229
telemt_me_idle_close_by_peer_total 229
telemt_me_route_drop_no_conn_total 293504
telemt_me_route_drop_channel_closed_total 103
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 618220
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
telemt_desync_total 4989
telemt_desync_full_logged_total 1401
telemt_desync_suppressed_total 3588
telemt_desync_frames_bucket_total{bucket="1_2"} 1616
telemt_desync_frames_bucket_total{bucket="3_10"} 1862
telemt_desync_frames_bucket_total{bucket="gt_10"} 1511
telemt_pool_swap_total 40
telemt_pool_force_close_total 1079
telemt_me_writer_close_signal_drop_total 112
telemt_me_draining_writers_reap_progress_total 13401
telemt_me_writer_removed_unexpected_total 226
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 930
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 12684
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1064
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 12322
telemt_me_writer_teardown_success_total{mode="normal"} 13614
telemt_me_writer_teardown_noop_total 13402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25859
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 26203
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 26637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 26903
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 27005
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 27016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 27016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 27016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 27016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 27016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 27016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 27016
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 29.378006
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 27016
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 112
telemt_me_refill_failed_total 10
telemt_me_writer_restored_same_endpoint_total 212
telemt_me_writer_removed_unexpected_minus_restored_total 14
telemt_user_connections_total{user="hello"} 617032
telemt_user_connections_current{user="hello"} 1500
telemt_user_octets_from_client{user="hello"} 8489839580 (7.91 GB)
telemt_user_octets_to_client{user="hello"} 210948559988 (196.46 GB)
telemt_user_unique_ips_current{user="hello"} 591
telemt_user_unique_ips_recent_window{user="hello"} 233
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 49699.7 (13h 48m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1220860
telemt_connections_bad_total 119957
telemt_connections_current 1385
telemt_connections_me_current 1385
telemt_handshake_timeouts_total 38533
telemt_upstream_connect_attempt_total 26250
telemt_upstream_connect_success_total 25860
telemt_upstream_connect_fail_total 339
telemt_upstream_connect_attempts_per_request{bucket="1"} 26199
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13173
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12631
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 56
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 339
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 1958
telemt_me_reconnect_success_total 788
telemt_me_reader_eof_total 686
telemt_me_idle_close_by_peer_total 686
telemt_me_route_drop_no_conn_total 460993
telemt_me_route_drop_channel_closed_total 3
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 920096
telemt_me_endpoint_quarantine_total 458
telemt_me_single_endpoint_outage_enter_total 22
telemt_me_single_endpoint_outage_exit_total 22
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 397
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
telemt_me_writers_active_current 42
telemt_desync_total 3974
telemt_desync_full_logged_total 2321
telemt_desync_suppressed_total 1653
telemt_desync_frames_bucket_total{bucket="1_2"} 835
telemt_desync_frames_bucket_total{bucket="3_10"} 1538
telemt_desync_frames_bucket_total{bucket="gt_10"} 1601
telemt_pool_swap_total 53
telemt_pool_force_close_total 1391
telemt_me_writer_close_signal_drop_total 114
telemt_me_draining_writers_reap_progress_total 20416
telemt_me_writer_removed_unexpected_total 659
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1821
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19240
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1323
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 68
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 19025
telemt_me_writer_teardown_success_total{mode="normal"} 21061
telemt_me_writer_teardown_noop_total 20416
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 40662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 41161
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 41344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 41463
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 41475
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 41477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 41477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 41477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 41477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 41477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 41477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 41477
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 41477
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 5.318901
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 41477
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 114
telemt_me_refill_failed_total 60
telemt_me_writer_restored_same_endpoint_total 598
telemt_me_writer_restored_fallback_total 17
telemt_me_async_recovery_trigger_total 16
telemt_me_writer_removed_unexpected_minus_restored_total 44
telemt_user_connections_total{user="hello"} 921849
telemt_user_connections_current{user="hello"} 1385
telemt_user_octets_from_client{user="hello"} 14740245686 (13.73 GB)
telemt_user_octets_to_client{user="hello"} 339067091211 (315.78 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 930
telemt_user_unique_ips_recent_window{user="hello"} 438
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 124559.9 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8944099
telemt_connections_bad_total 824959
telemt_connections_current 3917
telemt_connections_me_current 3917
telemt_handshake_timeouts_total 280398
telemt_upstream_connect_attempt_total 46069
telemt_upstream_connect_success_total 45990
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 45998
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20786
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25010
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 188
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1752
telemt_me_reconnect_success_total 914
telemt_me_reader_eof_total 917
telemt_me_idle_close_by_peer_total 917
telemt_me_route_drop_no_conn_total 4854032
telemt_me_route_drop_channel_closed_total 73
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7051024
telemt_me_endpoint_quarantine_total 789
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 937
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
telemt_desync_total 30430
telemt_desync_full_logged_total 10071
telemt_desync_suppressed_total 20359
telemt_desync_frames_bucket_total{bucket="1_2"} 6610
telemt_desync_frames_bucket_total{bucket="3_10"} 11830
telemt_desync_frames_bucket_total{bucket="gt_10"} 11990
telemt_pool_swap_total 135
telemt_pool_force_close_total 4457
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 673
telemt_me_draining_writers_reap_progress_total 42057
telemt_me_writer_removed_unexpected_total 881
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3496
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38942
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4188
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 269
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37600
telemt_me_writer_teardown_success_total{mode="normal"} 42438
telemt_me_writer_teardown_noop_total 42101
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 77540
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79627
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80754
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 82423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83597
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84219
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84528
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84539
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 177.303137
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84539
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 673
telemt_me_refill_failed_total 44
telemt_me_writer_restored_same_endpoint_total 815
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 61
telemt_user_connections_total{user="hello"} 7041755
telemt_user_connections_current{user="hello"} 3917
telemt_user_octets_from_client{user="hello"} 118957546640 (110.79 GB)
telemt_user_octets_to_client{user="hello"} 2409364023840 (2.19 TB)
telemt_user_unique_ips_current{user="hello"} 1562
telemt_user_unique_ips_recent_window{user="hello"} 618
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 124561.1 (34h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7371088
telemt_connections_bad_total 650001
telemt_connections_current 4233
telemt_connections_me_current 4233
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 242641
telemt_upstream_connect_attempt_total 50095
telemt_upstream_connect_success_total 49689
telemt_upstream_connect_fail_total 209
telemt_upstream_connect_attempts_per_request{bucket="1"} 49898
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24512
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24585
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 559
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 209
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2628
telemt_me_reconnect_success_total 987
telemt_me_reader_eof_total 953
telemt_me_idle_close_by_peer_total 953
telemt_me_route_drop_no_conn_total 2479656
telemt_me_route_drop_channel_closed_total 303
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5464157
telemt_me_endpoint_quarantine_total 789
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 958
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
telemt_me_writers_active_current 44
telemt_desync_total 25104
telemt_desync_full_logged_total 8624
telemt_desync_suppressed_total 16480
telemt_desync_frames_bucket_total{bucket="1_2"} 6014
telemt_desync_frames_bucket_total{bucket="3_10"} 9735
telemt_desync_frames_bucket_total{bucket="gt_10"} 9355
telemt_pool_swap_total 136
telemt_pool_force_close_total 4060
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 420
telemt_me_draining_writers_reap_progress_total 40535
telemt_me_writer_removed_unexpected_total 930
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3365
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38029
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 236
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 36475
telemt_me_writer_teardown_success_total{mode="normal"} 41394
telemt_me_writer_teardown_noop_total 40541
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 78086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 79899
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 80595
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81254
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 81717
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 81915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 81935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 81935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 81935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 81935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 81935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 81935
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 81935
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 53.943948
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 81935
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 420
telemt_me_refill_failed_total 92
telemt_me_writer_restored_same_endpoint_total 863
telemt_me_writer_restored_fallback_total 10
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 57
telemt_user_connections_total{user="hello"} 5385185
telemt_user_connections_current{user="hello"} 4233
telemt_user_octets_from_client{user="hello"} 153354547209 (142.82 GB)
telemt_user_octets_to_client{user="hello"} 2604236086991 (2.37 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1620
telemt_user_unique_ips_recent_window{user="hello"} 551
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 124525.4 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7144074
telemt_connections_bad_total 588601
telemt_connections_current 3619
telemt_connections_me_current 3619
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 238429
telemt_upstream_connect_attempt_total 56583
telemt_upstream_connect_success_total 55927
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 56074
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27642
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26139
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 867
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1279
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 205
telemt_me_reconnect_attempts_total 2696
telemt_me_reconnect_success_total 1166
telemt_me_reader_eof_total 1081
telemt_me_idle_close_by_peer_total 1081
telemt_me_route_drop_no_conn_total 2818370
telemt_me_route_drop_channel_closed_total 170
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5329959
telemt_me_endpoint_quarantine_total 877
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 923
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
telemt_desync_total 24937
telemt_desync_full_logged_total 8487
telemt_desync_suppressed_total 16450
telemt_desync_frames_bucket_total{bucket="1_2"} 6052
telemt_desync_frames_bucket_total{bucket="3_10"} 9560
telemt_desync_frames_bucket_total{bucket="gt_10"} 9325
telemt_pool_swap_total 133
telemt_pool_force_close_total 3895
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 449
telemt_me_draining_writers_reap_progress_total 41353
telemt_me_writer_removed_unexpected_total 1092
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3662
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 38797
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3637
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 258
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37458
telemt_me_writer_teardown_success_total{mode="normal"} 42459
telemt_me_writer_teardown_noop_total 41365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82253
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82793
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83396
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 83688
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 83774
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 83822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 83822
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 83824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 83824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 83824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 83824
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 83824
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 41.860412
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 83824
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 449
telemt_me_refill_failed_total 83
telemt_me_writer_restored_same_endpoint_total 1010
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 5323777
telemt_user_connections_current{user="hello"} 3619
telemt_user_octets_from_client{user="hello"} 141927775903 (132.18 GB)
telemt_user_octets_to_client{user="hello"} 2377498443747 (2.16 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1460
telemt_user_unique_ips_recent_window{user="hello"} 616
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 124564.0 (34h 36m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 22796414
telemt_connections_bad_total 1910985
telemt_connections_current 5669
telemt_connections_me_current 5669
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 676608
telemt_upstream_connect_attempt_total 238850
telemt_upstream_connect_success_total 219216
telemt_upstream_connect_fail_total 17678
telemt_upstream_connect_attempts_per_request{bucket="1"} 236894
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 154246
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 51458
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2477
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11035
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17678
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 66409
telemt_me_reconnect_success_total 2632
telemt_me_reader_eof_total 1657
telemt_me_idle_close_by_peer_total 1655
telemt_me_route_drop_no_conn_total 43371346
telemt_me_route_drop_channel_closed_total 137
telemt_me_route_drop_queue_full_total 13
telemt_me_route_drop_queue_full_profile_total{profile="high"} 13
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 18354757
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 973
telemt_me_single_endpoint_outage_enter_total 156
telemt_me_single_endpoint_outage_exit_total 156
telemt_me_single_endpoint_outage_reconnect_attempt_total 325
telemt_me_single_endpoint_outage_reconnect_success_total 82
telemt_me_single_endpoint_quarantine_bypass_total 325
telemt_me_single_endpoint_shadow_rotate_total 976
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
telemt_desync_total 35602
telemt_desync_full_logged_total 10653
telemt_desync_suppressed_total 24949
telemt_desync_frames_bucket_total{bucket="1_2"} 7899
telemt_desync_frames_bucket_total{bucket="3_10"} 15774
telemt_desync_frames_bucket_total{bucket="gt_10"} 11929
telemt_pool_swap_total 129
telemt_pool_force_close_total 4090
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 935
telemt_me_draining_writers_reap_progress_total 38977
telemt_me_writer_removed_unexpected_total 2435
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5271
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 35872
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3507
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 583
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 34887
telemt_me_writer_teardown_success_total{mode="normal"} 41143
telemt_me_writer_teardown_noop_total 39009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 72585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 75409
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 76821
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 78643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 79657
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 80016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 80108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 80117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 80125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 80136
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 80139
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 80147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 80152
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 280.400907
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 80152
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 935
telemt_me_refill_failed_total 3863
telemt_me_writer_restored_same_endpoint_total 1792
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 669
telemt_me_async_recovery_trigger_total 14705
telemt_me_writer_removed_unexpected_minus_restored_total 621
telemt_user_connections_total{user="hello"} 18519408
telemt_user_connections_current{user="hello"} 5669
telemt_user_octets_from_client{user="hello"} 270023610079 (251.48 GB)
telemt_user_octets_to_client{user="hello"} 1398555303026 (1.27 TB)
telemt_user_msgs_from_client{user="hello"} 500908
telemt_user_msgs_to_client{user="hello"} 1006528
telemt_user_unique_ips_current{user="hello"} 2023
telemt_user_unique_ips_recent_window{user="hello"} 1164
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 124531.5 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6816179
telemt_connections_bad_total 627831
telemt_connections_current 3252
telemt_connections_me_current 3252
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 141142
telemt_upstream_connect_attempt_total 65126
telemt_upstream_connect_success_total 64382
telemt_upstream_connect_fail_total 638
telemt_upstream_connect_attempts_per_request{bucket="1"} 65020
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36865
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27151
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 365
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 638
telemt_me_reconnect_attempts_total 70004
telemt_me_reconnect_success_total 1922
telemt_me_reader_eof_total 1699
telemt_me_idle_close_by_peer_total 1698
telemt_me_route_drop_no_conn_total 2616517
telemt_me_route_drop_channel_closed_total 12
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5330417
telemt_me_endpoint_quarantine_total 833
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 946
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
telemt_desync_total 26738
telemt_desync_full_logged_total 9300
telemt_desync_suppressed_total 17438
telemt_desync_frames_bucket_total{bucket="1_2"} 5352
telemt_desync_frames_bucket_total{bucket="3_10"} 10257
telemt_desync_frames_bucket_total{bucket="gt_10"} 11129
telemt_pool_swap_total 130
telemt_pool_force_close_total 3733
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 441
telemt_me_draining_writers_reap_progress_total 43680
telemt_me_writer_removed_unexpected_total 1730
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4377
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41070
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3318
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 415
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 39947
telemt_me_writer_teardown_success_total{mode="normal"} 45447
telemt_me_writer_teardown_noop_total 43681
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89125
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89128
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89128
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.033452
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89128
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 441
telemt_me_refill_failed_total 4217
telemt_me_writer_restored_same_endpoint_total 1606
telemt_me_writer_restored_fallback_total 38
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7313
telemt_me_writer_removed_unexpected_minus_restored_total 86
telemt_user_connections_total{user="hello"} 5321670
telemt_user_connections_current{user="hello"} 3252
telemt_user_octets_from_client{user="hello"} 136024203392 (126.68 GB)
telemt_user_octets_to_client{user="hello"} 2226526160022 (2.03 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1293
telemt_user_unique_ips_recent_window{user="hello"} 556
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 61367.4 (17h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5037045
telemt_connections_bad_total 204707
telemt_connections_current 4153
telemt_connections_me_current 4153
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1993319
telemt_upstream_connect_attempt_total 33996
telemt_upstream_connect_success_total 33763
telemt_upstream_connect_fail_total 226
telemt_upstream_connect_attempts_per_request{bucket="1"} 33989
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 20247
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13429
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 87
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 226
telemt_me_reconnect_attempts_total 46211
telemt_me_reconnect_success_total 1072
telemt_me_reader_eof_total 763
telemt_me_idle_close_by_peer_total 763
telemt_me_route_drop_no_conn_total 1238142
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2511524
telemt_me_endpoint_quarantine_total 433
telemt_me_single_endpoint_outage_enter_total 12
telemt_me_single_endpoint_outage_exit_total 12
telemt_me_single_endpoint_outage_reconnect_attempt_total 51
telemt_me_single_endpoint_outage_reconnect_success_total 12
telemt_me_single_endpoint_quarantine_bypass_total 51
telemt_me_single_endpoint_shadow_rotate_total 470
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 13424
telemt_desync_full_logged_total 4622
telemt_desync_suppressed_total 8802
telemt_desync_frames_bucket_total{bucket="1_2"} 2662
telemt_desync_frames_bucket_total{bucket="3_10"} 5130
telemt_desync_frames_bucket_total{bucket="gt_10"} 5632
telemt_pool_swap_total 67
telemt_pool_force_close_total 1943
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 171
telemt_me_draining_writers_reap_progress_total 22376
telemt_me_writer_removed_unexpected_total 833
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1881
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21350
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1718
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 225
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20433
telemt_me_writer_teardown_success_total{mode="normal"} 23231
telemt_me_writer_teardown_noop_total 22378
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45016
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45341
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45609
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.869288
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45609
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 171
telemt_me_refill_failed_total 2622
telemt_me_writer_restored_same_endpoint_total 956
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 2513302
telemt_user_connections_current{user="hello"} 4153
telemt_user_octets_from_client{user="hello"} 64557054120 (60.12 GB)
telemt_user_octets_to_client{user="hello"} 1115937222826 (1.01 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1768
telemt_user_unique_ips_recent_window{user="hello"} 507
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 42338.2 (11h 45m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 325720
telemt_connections_bad_total 2284
telemt_connections_current 816
telemt_connections_me_current 816
telemt_handshake_timeouts_total 7387
telemt_upstream_connect_attempt_total 20295
telemt_upstream_connect_success_total 20242
telemt_upstream_connect_fail_total 49
telemt_upstream_connect_attempts_per_request{bucket="1"} 20291
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 8504
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 11623
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 115
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 49
telemt_me_reconnect_attempts_total 842
telemt_me_reconnect_success_total 293
telemt_me_reader_eof_total 288
telemt_me_idle_close_by_peer_total 288
telemt_me_route_drop_no_conn_total 97899
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 294908
telemt_me_endpoint_quarantine_total 397
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 364
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 6
telemt_me_floor_mode{mode="adaptive"} 1
telemt_me_adaptive_floor_cpu_cores_detected 2
telemt_me_adaptive_floor_cpu_cores_effective 2
telemt_me_adaptive_floor_global_cap_raw 128
telemt_me_adaptive_floor_global_cap_effective 128
telemt_me_adaptive_floor_target_writers_total 37
telemt_me_adaptive_floor_active_cap_configured 128
telemt_me_adaptive_floor_active_cap_effective 128
telemt_me_adaptive_floor_warm_cap_configured 128
telemt_me_adaptive_floor_warm_cap_effective 128
telemt_me_writers_active_current 47
telemt_me_writers_warm_current 8
telemt_desync_total 1445
telemt_desync_full_logged_total 403
telemt_desync_suppressed_total 1042
telemt_desync_frames_bucket_total{bucket="1_2"} 469
telemt_desync_frames_bucket_total{bucket="3_10"} 552
telemt_desync_frames_bucket_total{bucket="gt_10"} 424
telemt_pool_swap_total 46
telemt_pool_force_close_total 1032
telemt_me_writer_close_signal_drop_total 39
telemt_me_draining_writers_reap_progress_total 18359
telemt_me_writer_removed_unexpected_total 275
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1193
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 17454
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1030
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 17327
telemt_me_writer_teardown_success_total{mode="normal"} 18647
telemt_me_writer_teardown_noop_total 18359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 36706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 36966
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36996
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 37006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 37006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 37006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 37006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 37006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 37006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 37006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 37006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 37006
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 37006
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.479846
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 37006
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 39
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 251
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 22
telemt_user_connections_total{user="hello"} 294488
telemt_user_connections_current{user="hello"} 816
telemt_user_octets_from_client{user="hello"} 4838691356 (4.51 GB)
telemt_user_octets_to_client{user="hello"} 167407417244 (155.91 GB)
telemt_user_unique_ips_current{user="hello"} 305
telemt_user_unique_ips_recent_window{user="hello"} 118
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 124536.7 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8323715
telemt_connections_bad_total 890787
telemt_connections_current 3871
telemt_connections_me_current 3871
telemt_handshake_timeouts_total 234074
telemt_upstream_connect_attempt_total 48873
telemt_upstream_connect_success_total 48693
telemt_upstream_connect_fail_total 141
telemt_upstream_connect_attempts_per_request{bucket="1"} 48834
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24137
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 24515
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 141
telemt_me_reconnect_attempts_total 1824
telemt_me_reconnect_success_total 988
telemt_me_reader_eof_total 965
telemt_me_idle_close_by_peer_total 965
telemt_me_route_drop_no_conn_total 2338227
telemt_me_route_drop_channel_closed_total 57
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6184537
telemt_me_endpoint_quarantine_total 889
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 952
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
telemt_desync_total 24671
telemt_desync_full_logged_total 8096
telemt_desync_suppressed_total 16575
telemt_desync_frames_bucket_total{bucket="1_2"} 6116
telemt_desync_frames_bucket_total{bucket="3_10"} 8999
telemt_desync_frames_bucket_total{bucket="gt_10"} 9556
telemt_pool_swap_total 138
telemt_pool_force_close_total 3687
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 438
telemt_me_draining_writers_reap_progress_total 44121
telemt_me_writer_removed_unexpected_total 927
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3485
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41591
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3594
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 93
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40434
telemt_me_writer_teardown_success_total{mode="normal"} 45076
telemt_me_writer_teardown_noop_total 44123
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87702
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88706
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 88901
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89108
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89199
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89199
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.383756
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89199
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 438
telemt_me_refill_failed_total 43
telemt_me_writer_restored_same_endpoint_total 872
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 46
telemt_user_connections_total{user="hello"} 6158382
telemt_user_connections_current{user="hello"} 3871
telemt_user_octets_from_client{user="hello"} 121324885276 (112.99 GB)
telemt_user_octets_to_client{user="hello"} 2891834266264 (2.63 TB)
telemt_user_unique_ips_current{user="hello"} 1472
telemt_user_unique_ips_recent_window{user="hello"} 616
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 124532.5 (34h 35m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7277771
telemt_connections_bad_total 777403
telemt_connections_current 4565
telemt_connections_me_current 4565
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 193972
telemt_upstream_connect_attempt_total 64690
telemt_upstream_connect_success_total 64197
telemt_upstream_connect_fail_total 430
telemt_upstream_connect_attempts_per_request{bucket="1"} 64627
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 36891
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26171
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 617
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 430
telemt_me_reconnect_attempts_total 6007
telemt_me_reconnect_success_total 1375
telemt_me_reader_eof_total 1239
telemt_me_idle_close_by_peer_total 1239
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2403901
telemt_me_route_drop_channel_closed_total 199
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5537336
telemt_me_endpoint_quarantine_total 978
telemt_me_single_endpoint_outage_enter_total 30
telemt_me_single_endpoint_outage_exit_total 30
telemt_me_single_endpoint_outage_reconnect_attempt_total 30
telemt_me_single_endpoint_outage_reconnect_success_total 28
telemt_me_single_endpoint_quarantine_bypass_total 30
telemt_me_single_endpoint_shadow_rotate_total 950
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
telemt_me_writers_active_current 81
telemt_desync_total 23597
telemt_desync_full_logged_total 7839
telemt_desync_suppressed_total 15758
telemt_desync_frames_bucket_total{bucket="1_2"} 5846
telemt_desync_frames_bucket_total{bucket="3_10"} 8665
telemt_desync_frames_bucket_total{bucket="gt_10"} 9086
telemt_pool_swap_total 135
telemt_pool_force_close_total 3610
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 437
telemt_me_draining_writers_reap_progress_total 42562
telemt_me_writer_removed_unexpected_total 1254
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4052
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39825
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3378
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 232
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38952
telemt_me_writer_teardown_success_total{mode="normal"} 43877
telemt_me_writer_teardown_noop_total 42566
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 84587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 85745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 86180
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86443
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.455184
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86443
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 437
telemt_me_refill_failed_total 267
telemt_me_writer_restored_same_endpoint_total 1074
telemt_me_writer_restored_fallback_total 81
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 82
telemt_me_writer_removed_unexpected_minus_restored_total 99
telemt_user_connections_total{user="hello"} 5539180
telemt_user_connections_current{user="hello"} 4565
telemt_user_octets_from_client{user="hello"} 102558364025 (95.51 GB)
telemt_user_octets_to_client{user="hello"} 2406389945684 (2.19 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1815
telemt_user_unique_ips_recent_window{user="hello"} 490
```