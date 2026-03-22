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

# Server Metrics 2026-03-22 08:28:31 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 40928.3 (11h 22m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 963158
telemt_connections_bad_total 56317
telemt_connections_current 1654
telemt_connections_me_current 1654
telemt_handshake_timeouts_total 44845
telemt_upstream_connect_attempt_total 16323
telemt_upstream_connect_success_total 16322
telemt_upstream_connect_attempts_per_request{bucket="1"} 16322
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 5651
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 10622
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 38
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 3
telemt_me_reconnect_attempts_total 477
telemt_me_reconnect_success_total 251
telemt_me_reader_eof_total 249
telemt_me_idle_close_by_peer_total 249
telemt_me_route_drop_no_conn_total 545023
telemt_me_route_drop_channel_closed_total 173
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 801151
telemt_me_endpoint_quarantine_total 295
telemt_me_single_endpoint_shadow_rotate_total 330
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
telemt_me_writers_active_current 43
telemt_desync_total 5965
telemt_desync_full_logged_total 1677
telemt_desync_suppressed_total 4288
telemt_desync_frames_bucket_total{bucket="1_2"} 1842
telemt_desync_frames_bucket_total{bucket="3_10"} 2241
telemt_desync_frames_bucket_total{bucket="gt_10"} 1882
telemt_pool_swap_total 45
telemt_pool_force_close_total 1268
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 143
telemt_me_draining_writers_reap_progress_total 14840
telemt_me_writer_removed_unexpected_total 246
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1031
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 14006
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1242
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 26
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 13572
telemt_me_writer_teardown_success_total{mode="normal"} 15037
telemt_me_writer_teardown_noop_total 14842
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 27405
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 28038
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 28509
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 29202
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 29682
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 29855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 29879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 29879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 29879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 29879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 29879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 29879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 29879
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 49.007248
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 29879
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 143
telemt_me_refill_failed_total 12
telemt_me_writer_restored_same_endpoint_total 229
telemt_me_writer_removed_unexpected_minus_restored_total 17
telemt_user_connections_total{user="hello"} 799636
telemt_user_connections_current{user="hello"} 1654
telemt_user_octets_from_client{user="hello"} 10827885496 (10.08 GB)
telemt_user_octets_to_client{user="hello"} 257467093912 (239.78 GB)
telemt_user_unique_ips_current{user="hello"} 607
telemt_user_unique_ips_recent_window{user="hello"} 252
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 54294.4 (15h 4m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1454078
telemt_connections_bad_total 143547
telemt_connections_current 1263
telemt_connections_me_current 1263
telemt_handshake_timeouts_total 42125
telemt_upstream_connect_attempt_total 28531
telemt_upstream_connect_success_total 28106
telemt_upstream_connect_fail_total 373
telemt_upstream_connect_attempts_per_request{bucket="1"} 28479
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14164
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 13881
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 61
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 373
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 2461
telemt_me_reconnect_success_total 1060
telemt_me_reader_eof_total 962
telemt_me_idle_close_by_peer_total 962
telemt_me_route_drop_no_conn_total 616785
telemt_me_route_drop_channel_closed_total 8
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1095602
telemt_me_endpoint_quarantine_total 480
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 24
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 24
telemt_me_single_endpoint_shadow_rotate_total 432
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 27
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
telemt_desync_total 4875
telemt_desync_full_logged_total 2823
telemt_desync_suppressed_total 2052
telemt_desync_frames_bucket_total{bucket="1_2"} 1062
telemt_desync_frames_bucket_total{bucket="3_10"} 1892
telemt_desync_frames_bucket_total{bucket="gt_10"} 1921
telemt_pool_swap_total 56
telemt_pool_force_close_total 1551
telemt_me_writer_close_signal_drop_total 128
telemt_me_draining_writers_reap_progress_total 22303
telemt_me_writer_removed_unexpected_total 932
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2197
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 21027
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1427
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 124
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 20752
telemt_me_writer_teardown_success_total{mode="normal"} 23224
telemt_me_writer_teardown_noop_total 22303
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 44621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 45170
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 45363
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 45513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 45525
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 45527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 45527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 45527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 45527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 45527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 45527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 45527
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 45527
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.063620
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 45527
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 128
telemt_me_refill_failed_total 67
telemt_me_writer_restored_same_endpoint_total 858
telemt_me_writer_restored_fallback_total 19
telemt_me_async_recovery_trigger_total 19
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 1097171
telemt_user_connections_current{user="hello"} 1263
telemt_user_octets_from_client{user="hello"} 17057256942 (15.89 GB)
telemt_user_octets_to_client{user="hello"} 388022504755 (361.37 GB)
telemt_user_msgs_from_client{user="hello"} 6406
telemt_user_msgs_to_client{user="hello"} 10605
telemt_user_unique_ips_current{user="hello"} 801
telemt_user_unique_ips_recent_window{user="hello"} 571
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 129154.2 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9637077
telemt_connections_bad_total 867418
telemt_connections_current 5047
telemt_connections_me_current 5047
telemt_handshake_timeouts_total 290456
telemt_upstream_connect_attempt_total 47694
telemt_upstream_connect_success_total 47614
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 47622
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21497
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25920
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 191
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1895
telemt_me_reconnect_success_total 984
telemt_me_reader_eof_total 992
telemt_me_idle_close_by_peer_total 992
telemt_me_route_drop_no_conn_total 5388916
telemt_me_route_drop_channel_closed_total 81
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7562555
telemt_me_endpoint_quarantine_total 810
telemt_me_single_endpoint_outage_enter_total 6
telemt_me_single_endpoint_outage_exit_total 6
telemt_me_single_endpoint_outage_reconnect_attempt_total 6
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 6
telemt_me_single_endpoint_shadow_rotate_total 969
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
telemt_desync_total 32828
telemt_desync_full_logged_total 10804
telemt_desync_suppressed_total 22024
telemt_desync_frames_bucket_total{bucket="1_2"} 7198
telemt_desync_frames_bucket_total{bucket="3_10"} 12737
telemt_desync_frames_bucket_total{bucket="gt_10"} 12893
telemt_pool_swap_total 139
telemt_pool_force_close_total 4628
telemt_pool_stale_pick_total 18
telemt_me_writer_close_signal_drop_total 704
telemt_me_draining_writers_reap_progress_total 43530
telemt_me_writer_removed_unexpected_total 954
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3660
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40299
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4319
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 309
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38902
telemt_me_writer_teardown_success_total{mode="normal"} 43959
telemt_me_writer_teardown_noop_total 43574
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 83617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 85344
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86551
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 87193
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 87521
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 87533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 87533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 87533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 87533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 87533
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 87533
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 185.296505
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 87533
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 704
telemt_me_refill_failed_total 48
telemt_me_writer_restored_same_endpoint_total 882
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 10
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 7552837
telemt_user_connections_current{user="hello"} 5047
telemt_user_octets_from_client{user="hello"} 125135923532 (116.54 GB)
telemt_user_octets_to_client{user="hello"} 2530560040772 (2.30 TB)
telemt_user_unique_ips_current{user="hello"} 1874
telemt_user_unique_ips_recent_window{user="hello"} 677
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 129155.5 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7870147
telemt_connections_bad_total 700028
telemt_connections_current 4092
telemt_connections_me_current 4092
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 253940
telemt_upstream_connect_attempt_total 53703
telemt_upstream_connect_success_total 53227
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 53470
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25968
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26029
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 108
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1122
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 2822
telemt_me_reconnect_success_total 1071
telemt_me_reader_eof_total 993
telemt_me_idle_close_by_peer_total 993
telemt_me_route_drop_no_conn_total 2640488
telemt_me_route_drop_channel_closed_total 315
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5823763
telemt_me_endpoint_quarantine_total 817
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 22
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 22
telemt_me_single_endpoint_shadow_rotate_total 996
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 26604
telemt_desync_full_logged_total 9123
telemt_desync_suppressed_total 17481
telemt_desync_frames_bucket_total{bucket="1_2"} 6383
telemt_desync_frames_bucket_total{bucket="3_10"} 10298
telemt_desync_frames_bucket_total{bucket="gt_10"} 9923
telemt_pool_swap_total 141
telemt_pool_force_close_total 4213
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 452
telemt_me_draining_writers_reap_progress_total 41745
telemt_me_writer_removed_unexpected_total 1014
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3556
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 39116
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3965
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 248
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 37532
telemt_me_writer_teardown_success_total{mode="normal"} 42672
telemt_me_writer_teardown_noop_total 41751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 80268
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 82241
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 82981
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 83699
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 84196
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 84403
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 84423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 84423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 84423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 84423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 84423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 84423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 84423
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 57.345727
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 84423
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 452
telemt_me_refill_failed_total 97
telemt_me_writer_restored_same_endpoint_total 908
telemt_me_writer_restored_fallback_total 12
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 206
telemt_me_writer_removed_unexpected_minus_restored_total 94
telemt_user_connections_total{user="hello"} 5746394
telemt_user_connections_current{user="hello"} 4092
telemt_user_octets_from_client{user="hello"} 159594627275 (148.63 GB)
telemt_user_octets_to_client{user="hello"} 2761405989334 (2.51 TB)
telemt_user_msgs_from_client{user="hello"} 42822
telemt_user_msgs_to_client{user="hello"} 51589
telemt_user_unique_ips_current{user="hello"} 1566
telemt_user_unique_ips_recent_window{user="hello"} 605
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 129119.6 (35h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7582832
telemt_connections_bad_total 627569
telemt_connections_current 3885
telemt_connections_me_current 3885
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 250838
telemt_upstream_connect_attempt_total 58129
telemt_upstream_connect_success_total 57455
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 57602
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28239
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26984
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 925
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1307
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_keepalive_timeout_total 237
telemt_me_reconnect_attempts_total 2822
telemt_me_reconnect_success_total 1218
telemt_me_reader_eof_total 1117
telemt_me_idle_close_by_peer_total 1117
telemt_me_route_drop_no_conn_total 3047230
telemt_me_route_drop_channel_closed_total 184
telemt_me_route_drop_queue_full_total 7
telemt_me_route_drop_queue_full_profile_total{profile="high"} 7
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5653976
telemt_me_endpoint_quarantine_total 911
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 18
telemt_me_single_endpoint_outage_reconnect_success_total 15
telemt_me_single_endpoint_quarantine_bypass_total 18
telemt_me_single_endpoint_shadow_rotate_total 954
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 50
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
telemt_desync_total 26478
telemt_desync_full_logged_total 9008
telemt_desync_suppressed_total 17470
telemt_desync_frames_bucket_total{bucket="1_2"} 6383
telemt_desync_frames_bucket_total{bucket="3_10"} 10171
telemt_desync_frames_bucket_total{bucket="gt_10"} 9924
telemt_pool_swap_total 138
telemt_pool_force_close_total 4112
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 477
telemt_me_draining_writers_reap_progress_total 42755
telemt_me_writer_removed_unexpected_total 1128
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3807
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 40060
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 12
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3802
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 310
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 38643
telemt_me_writer_teardown_success_total{mode="normal"} 43867
telemt_me_writer_teardown_noop_total 42767
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 83117
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 84871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 85492
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 86154
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 86482
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 86582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 86632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 86632
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 86634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 86634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 86634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 86634
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 86634
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 46.148625
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 86634
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 477
telemt_me_refill_failed_total 87
telemt_me_writer_restored_same_endpoint_total 1055
telemt_me_writer_restored_fallback_total 6
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 67
telemt_user_connections_total{user="hello"} 5647046
telemt_user_connections_current{user="hello"} 3885
telemt_user_octets_from_client{user="hello"} 147168070219 (137.06 GB)
telemt_user_octets_to_client{user="hello"} 2511859491147 (2.28 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1563
telemt_user_unique_ips_recent_window{user="hello"} 550
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 129159.2 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 24413292
telemt_connections_bad_total 1991908
telemt_connections_current 5635
telemt_connections_me_current 5635
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 701623
telemt_upstream_connect_attempt_total 241772
telemt_upstream_connect_success_total 222003
telemt_upstream_connect_fail_total 17762
telemt_upstream_connect_attempts_per_request{bucket="1"} 239765
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 155444
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 52660
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 2724
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11175
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 17762
telemt_me_keepalive_timeout_total 485
telemt_me_reconnect_attempts_total 68113
telemt_me_reconnect_success_total 2746
telemt_me_reader_eof_total 1695
telemt_me_idle_close_by_peer_total 1693
telemt_me_route_drop_no_conn_total 47527760
telemt_me_route_drop_channel_closed_total 145
telemt_me_route_drop_queue_full_total 15
telemt_me_route_drop_queue_full_profile_total{profile="high"} 15
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 19756733
telemt_me_writer_pick_total{mode="p2c",result="full"} 227
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_writer_pick_blocking_fallback_total 222
telemt_me_endpoint_quarantine_total 1002
telemt_me_single_endpoint_outage_enter_total 165
telemt_me_single_endpoint_outage_exit_total 165
telemt_me_single_endpoint_outage_reconnect_attempt_total 336
telemt_me_single_endpoint_outage_reconnect_success_total 87
telemt_me_single_endpoint_quarantine_bypass_total 336
telemt_me_single_endpoint_shadow_rotate_total 1014
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 73
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
telemt_me_writers_active_current 74
telemt_desync_total 38427
telemt_desync_full_logged_total 11324
telemt_desync_suppressed_total 27103
telemt_desync_frames_bucket_total{bucket="1_2"} 8533
telemt_desync_frames_bucket_total{bucket="3_10"} 16955
telemt_desync_frames_bucket_total{bucket="gt_10"} 12939
telemt_pool_swap_total 134
telemt_pool_force_close_total 4256
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 977
telemt_me_draining_writers_reap_progress_total 40181
telemt_me_writer_removed_unexpected_total 2517
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5442
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 36981
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 29
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3653
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 603
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 35925
telemt_me_writer_teardown_success_total{mode="normal"} 42423
telemt_me_writer_teardown_noop_total 40213
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 74722
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 77712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 79172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 81066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 82131
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 82498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 82592
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 82601
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 82609
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 82620
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 82623
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 82631
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 82636
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 284.919061
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 82636
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 977
telemt_me_refill_failed_total 3959
telemt_me_writer_restored_same_endpoint_total 1870
telemt_me_writer_restored_fallback_total 22
telemt_me_no_writer_failfast_total 677
telemt_me_async_recovery_trigger_total 14906
telemt_me_writer_removed_unexpected_minus_restored_total 625
telemt_user_connections_total{user="hello"} 19922079
telemt_user_connections_current{user="hello"} 5635
telemt_user_octets_from_client{user="hello"} 279531296471 (260.33 GB)
telemt_user_octets_to_client{user="hello"} 1446594002867 (1.32 TB)
telemt_user_msgs_from_client{user="hello"} 503035
telemt_user_msgs_to_client{user="hello"} 1007896
telemt_user_unique_ips_current{user="hello"} 2103
telemt_user_unique_ips_recent_window{user="hello"} 1043
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 129126.4 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7214459
telemt_connections_bad_total 652833
telemt_connections_current 4462
telemt_connections_me_current 4462
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 148063
telemt_upstream_connect_attempt_total 66563
telemt_upstream_connect_success_total 65777
telemt_upstream_connect_fail_total 669
telemt_upstream_connect_attempts_per_request{bucket="1"} 66446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37502
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 27907
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 367
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 669
telemt_me_reconnect_attempts_total 70263
telemt_me_reconnect_success_total 1989
telemt_me_reader_eof_total 1750
telemt_me_idle_close_by_peer_total 1749
telemt_me_route_drop_no_conn_total 2815417
telemt_me_route_drop_channel_closed_total 13
telemt_me_route_drop_queue_full_total 40
telemt_me_route_drop_queue_full_profile_total{profile="high"} 40
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5667580
telemt_me_endpoint_quarantine_total 868
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 26
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 26
telemt_me_single_endpoint_shadow_rotate_total 979
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 37
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
telemt_desync_total 28552
telemt_desync_full_logged_total 9939
telemt_desync_suppressed_total 18613
telemt_desync_frames_bucket_total{bucket="1_2"} 5704
telemt_desync_frames_bucket_total{bucket="3_10"} 11004
telemt_desync_frames_bucket_total{bucket="gt_10"} 11844
telemt_pool_swap_total 135
telemt_pool_force_close_total 3895
telemt_pool_stale_pick_total 66
telemt_me_writer_close_signal_drop_total 461
telemt_me_draining_writers_reap_progress_total 44907
telemt_me_writer_removed_unexpected_total 1780
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4520
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42193
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3462
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 433
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41012
telemt_me_writer_teardown_success_total{mode="normal"} 46713
telemt_me_writer_teardown_noop_total 44908
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90089
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91365
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91587
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91618
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91621
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.357891
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91621
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 461
telemt_me_refill_failed_total 4226
telemt_me_writer_restored_same_endpoint_total 1651
telemt_me_writer_restored_fallback_total 40
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7319
telemt_me_writer_removed_unexpected_minus_restored_total 89
telemt_user_connections_total{user="hello"} 5658080
telemt_user_connections_current{user="hello"} 4462
telemt_user_octets_from_client{user="hello"} 142565983692 (132.77 GB)
telemt_user_octets_to_client{user="hello"} 2349611240442 (2.14 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 1788
telemt_user_unique_ips_recent_window{user="hello"} 554
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 65962.4 (18h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5636342
telemt_connections_bad_total 222068
telemt_connections_current 3359
telemt_connections_me_current 3359
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 2241065
telemt_upstream_connect_attempt_total 35674
telemt_upstream_connect_success_total 35424
telemt_upstream_connect_fail_total 243
telemt_upstream_connect_attempts_per_request{bucket="1"} 35667
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21063
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14271
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 90
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 243
telemt_me_reconnect_attempts_total 47364
telemt_me_reconnect_success_total 1172
telemt_me_reader_eof_total 843
telemt_me_idle_close_by_peer_total 843
telemt_me_route_drop_no_conn_total 1407662
telemt_me_route_drop_channel_closed_total 5
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2822116
telemt_me_endpoint_quarantine_total 459
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 52
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 52
telemt_me_single_endpoint_shadow_rotate_total 507
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
telemt_me_writers_active_current 52
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 15244
telemt_desync_full_logged_total 5198
telemt_desync_suppressed_total 10046
telemt_desync_frames_bucket_total{bucket="1_2"} 2964
telemt_desync_frames_bucket_total{bucket="3_10"} 5869
telemt_desync_frames_bucket_total{bucket="gt_10"} 6411
telemt_pool_swap_total 71
telemt_pool_force_close_total 2124
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 199
telemt_me_draining_writers_reap_progress_total 23851
telemt_me_writer_removed_unexpected_total 913
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2054
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 22732
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1852
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 272
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 21727
telemt_me_writer_teardown_success_total{mode="normal"} 24786
telemt_me_writer_teardown_noop_total 23857
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47945
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 48335
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 48510
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 48643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 48643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 48643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 48643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 48643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 48643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 48643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 48643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 48643
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 48643
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 4.525589
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 48643
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 199
telemt_me_refill_failed_total 2687
telemt_me_writer_restored_same_endpoint_total 1045
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 2823300
telemt_user_connections_current{user="hello"} 3359
telemt_user_octets_from_client{user="hello"} 72156699868 (67.20 GB)
telemt_user_octets_to_client{user="hello"} 1238627436758 (1.13 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1398
telemt_user_unique_ips_recent_window{user="hello"} 579
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 46932.9 (13h 2m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 405021
telemt_connections_bad_total 2785
telemt_connections_current 920
telemt_connections_me_current 920
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 8220
telemt_upstream_connect_attempt_total 24962
telemt_upstream_connect_success_total 24904
telemt_upstream_connect_fail_total 54
telemt_upstream_connect_attempts_per_request{bucket="1"} 24958
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 11762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 12907
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 235
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 54
telemt_me_reconnect_attempts_total 975
telemt_me_reconnect_success_total 351
telemt_me_reader_eof_total 345
telemt_me_idle_close_by_peer_total 345
telemt_me_route_drop_no_conn_total 126332
telemt_me_route_drop_channel_closed_total 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 365744
telemt_me_endpoint_quarantine_total 446
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 2
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 401
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 8
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
telemt_me_writers_active_current 58
telemt_me_writers_warm_current 32
telemt_desync_total 1666
telemt_desync_full_logged_total 487
telemt_desync_suppressed_total 1179
telemt_desync_frames_bucket_total{bucket="1_2"} 500
telemt_desync_frames_bucket_total{bucket="3_10"} 656
telemt_desync_frames_bucket_total{bucket="gt_10"} 510
telemt_pool_swap_total 51
telemt_pool_force_close_total 1142
telemt_me_writer_close_signal_drop_total 43
telemt_me_draining_writers_reap_progress_total 19977
telemt_me_writer_removed_unexpected_total 330
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1370
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 18952
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1139
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18835
telemt_me_writer_teardown_success_total{mode="normal"} 20322
telemt_me_writer_teardown_noop_total 19977
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 39961
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 40228
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 40289
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 40299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40299
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40299
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.822628
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40299
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 43
telemt_me_refill_failed_total 36
telemt_me_writer_restored_same_endpoint_total 300
telemt_me_writer_restored_fallback_total 2
telemt_me_async_recovery_trigger_total 26
telemt_me_writer_removed_unexpected_minus_restored_total 28
telemt_user_connections_total{user="hello"} 367938
telemt_user_connections_current{user="hello"} 920
telemt_user_octets_from_client{user="hello"} 7097495289 (6.61 GB)
telemt_user_octets_to_client{user="hello"} 191195367535 (178.06 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 332
telemt_user_unique_ips_recent_window{user="hello"} 150
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 129130.8 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 8874013
telemt_connections_bad_total 1010281
telemt_connections_current 5094
telemt_connections_me_current 5094
telemt_handshake_timeouts_total 246023
telemt_upstream_connect_attempt_total 50289
telemt_upstream_connect_success_total 50098
telemt_upstream_connect_fail_total 147
telemt_upstream_connect_attempts_per_request{bucket="1"} 50245
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24808
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 25249
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 147
telemt_me_reconnect_attempts_total 1893
telemt_me_reconnect_success_total 1026
telemt_me_reader_eof_total 997
telemt_me_idle_close_by_peer_total 997
telemt_me_route_drop_no_conn_total 2480308
telemt_me_route_drop_channel_closed_total 60
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6579706
telemt_me_endpoint_quarantine_total 918
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 982
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
telemt_me_writers_active_current 44
telemt_desync_total 26354
telemt_desync_full_logged_total 8651
telemt_desync_suppressed_total 17703
telemt_desync_frames_bucket_total{bucket="1_2"} 6502
telemt_desync_frames_bucket_total{bucket="3_10"} 9607
telemt_desync_frames_bucket_total{bucket="gt_10"} 10245
telemt_pool_swap_total 143
telemt_pool_force_close_total 3840
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 465
telemt_me_draining_writers_reap_progress_total 45390
telemt_me_writer_removed_unexpected_total 958
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3616
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 42761
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3741
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 99
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 41550
telemt_me_writer_teardown_success_total{mode="normal"} 46377
telemt_me_writer_teardown_noop_total 45392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 90191
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 91460
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 91678
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 91769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 91769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 91769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 91769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 91769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 91769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 91769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 91769
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 91769
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 11.862243
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 91769
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 465
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 898
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 24
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 6552802
telemt_user_connections_current{user="hello"} 5094
telemt_user_octets_from_client{user="hello"} 128217979252 (119.41 GB)
telemt_user_octets_to_client{user="hello"} 3078777729020 (2.80 TB)
telemt_user_unique_ips_current{user="hello"} 1808
telemt_user_unique_ips_recent_window{user="hello"} 679
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 129127.4 (35h 52m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7722428
telemt_connections_bad_total 852991
telemt_connections_current 4399
telemt_connections_me_current 4399
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 206533
telemt_upstream_connect_attempt_total 66323
telemt_upstream_connect_success_total 65811
telemt_upstream_connect_fail_total 446
telemt_upstream_connect_attempts_per_request{bucket="1"} 66257
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 37733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 26930
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 630
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 446
telemt_me_reconnect_attempts_total 6373
telemt_me_reconnect_success_total 1443
telemt_me_reader_eof_total 1294
telemt_me_idle_close_by_peer_total 1294
telemt_me_seq_mismatch_total 61
telemt_me_route_drop_no_conn_total 2610059
telemt_me_route_drop_channel_closed_total 221
telemt_me_route_drop_queue_full_total 14
telemt_me_route_drop_queue_full_profile_total{profile="high"} 14
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5876166
telemt_me_endpoint_quarantine_total 1010
telemt_me_single_endpoint_outage_enter_total 33
telemt_me_single_endpoint_outage_exit_total 33
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 980
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 39
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
telemt_desync_total 25267
telemt_desync_full_logged_total 8411
telemt_desync_suppressed_total 16856
telemt_desync_frames_bucket_total{bucket="1_2"} 6236
telemt_desync_frames_bucket_total{bucket="3_10"} 9289
telemt_desync_frames_bucket_total{bucket="gt_10"} 9742
telemt_pool_swap_total 140
telemt_pool_force_close_total 3786
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 461
telemt_me_draining_writers_reap_progress_total 44038
telemt_me_writer_removed_unexpected_total 1309
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4212
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 41197
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3517
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 269
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 40252
telemt_me_writer_teardown_success_total{mode="normal"} 45409
telemt_me_writer_teardown_noop_total 44042
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 87523
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 88739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 89186
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 89413
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 89451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 89451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 89451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 89451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 89451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 89451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 89451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 89451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 89451
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 12.796059
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 89451
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 461
telemt_me_refill_failed_total 285
telemt_me_writer_restored_same_endpoint_total 1127
telemt_me_writer_restored_fallback_total 84
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 112
telemt_me_writer_removed_unexpected_minus_restored_total 98
telemt_user_connections_total{user="hello"} 5877188
telemt_user_connections_current{user="hello"} 4399
telemt_user_octets_from_client{user="hello"} 108186457713 (100.76 GB)
telemt_user_octets_to_client{user="hello"} 2541758313772 (2.31 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1708
telemt_user_unique_ips_recent_window{user="hello"} 605
```