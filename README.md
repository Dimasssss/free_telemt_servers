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

# Server Metrics 2026-03-22 13:35:51 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 59368.4 (16h 29m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 1850267
telemt_connections_bad_total 82018
telemt_connections_current 1784
telemt_connections_me_current 1784
telemt_handshake_timeouts_total 79055
telemt_upstream_connect_attempt_total 22255
telemt_upstream_connect_success_total 22254
telemt_upstream_connect_attempts_per_request{bucket="1"} 22254
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 7690
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 14499
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 52
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 13
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 908
telemt_me_reconnect_success_total 362
telemt_me_reader_eof_total 366
telemt_me_idle_close_by_peer_total 366
telemt_me_route_drop_no_conn_total 1285490
telemt_me_route_drop_channel_closed_total 585
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1572681
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_endpoint_quarantine_total 407
telemt_me_single_endpoint_outage_enter_total 3
telemt_me_single_endpoint_outage_exit_total 3
telemt_me_single_endpoint_outage_reconnect_attempt_total 3
telemt_me_single_endpoint_outage_reconnect_success_total 3
telemt_me_single_endpoint_quarantine_bypass_total 3
telemt_me_single_endpoint_shadow_rotate_total 469
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 17
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
telemt_desync_total 8723
telemt_desync_full_logged_total 2667
telemt_desync_suppressed_total 6056
telemt_desync_frames_bucket_total{bucket="1_2"} 2436
telemt_desync_frames_bucket_total{bucket="3_10"} 3281
telemt_desync_frames_bucket_total{bucket="gt_10"} 3006
telemt_pool_swap_total 65
telemt_pool_force_close_total 1947
telemt_pool_stale_pick_total 2
telemt_me_writer_close_signal_drop_total 313
telemt_me_draining_writers_reap_progress_total 20292
telemt_me_writer_removed_unexpected_total 357
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1447
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 19064
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1911
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 36
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 18345
telemt_me_writer_teardown_success_total{mode="normal"} 20511
telemt_me_writer_teardown_noop_total 20296
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 34662
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 35918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 36992
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 38772
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 40055
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 40645
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 40804
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 40807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 40807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 40807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 40807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 40807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 40807
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 151.476630
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 40807
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 313
telemt_me_refill_failed_total 29
telemt_me_writer_restored_same_endpoint_total 321
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 1569773
telemt_user_connections_current{user="hello"} 1784
telemt_user_octets_from_client{user="hello"} 24678592772 (22.98 GB)
telemt_user_octets_to_client{user="hello"} 459242103628 (427.70 GB)
telemt_user_unique_ips_current{user="hello"} 671
telemt_user_unique_ips_recent_window{user="hello"} 293
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 72734.6 (20h 12m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3019809
telemt_connections_bad_total 282716
telemt_connections_current 1818
telemt_connections_me_current 1818
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 4
telemt_handshake_timeouts_total 70879
telemt_upstream_connect_attempt_total 46782
telemt_upstream_connect_success_total 46231
telemt_upstream_connect_fail_total 486
telemt_upstream_connect_attempts_per_request{bucket="1"} 46717
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27806
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 18292
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 133
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 486
telemt_me_keepalive_timeout_total 4
telemt_me_reconnect_attempts_total 3654
telemt_me_reconnect_success_total 1632
telemt_me_reader_eof_total 1503
telemt_me_idle_close_by_peer_total 1503
telemt_me_route_drop_no_conn_total 2817244
telemt_me_route_drop_channel_closed_total 28
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2374661
telemt_me_endpoint_quarantine_total 612
telemt_me_single_endpoint_outage_enter_total 35
telemt_me_single_endpoint_outage_exit_total 35
telemt_me_single_endpoint_outage_reconnect_attempt_total 35
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 35
telemt_me_single_endpoint_shadow_rotate_total 569
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 32
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
telemt_desync_total 9318
telemt_desync_full_logged_total 5209
telemt_desync_suppressed_total 4109
telemt_desync_frames_bucket_total{bucket="1_2"} 2190
telemt_desync_frames_bucket_total{bucket="3_10"} 3644
telemt_desync_frames_bucket_total{bucket="gt_10"} 3484
telemt_pool_swap_total 72
telemt_pool_force_close_total 2070
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 172
telemt_me_draining_writers_reap_progress_total 28694
telemt_me_writer_removed_unexpected_total 1460
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3140
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27015
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1824
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 246
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26624
telemt_me_writer_teardown_success_total{mode="normal"} 30155
telemt_me_writer_teardown_noop_total 28694
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57419
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 58321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 58564
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 58818
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 58846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 58849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 58849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 58849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 58849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 58849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 58849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 58849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 58849
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.738430
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 58849
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 172
telemt_me_refill_failed_total 91
telemt_me_writer_restored_same_endpoint_total 1353
telemt_me_writer_restored_fallback_total 24
telemt_me_async_recovery_trigger_total 35
telemt_me_writer_removed_unexpected_minus_restored_total 83
telemt_user_connections_total{user="hello"} 2386234
telemt_user_connections_current{user="hello"} 1818
telemt_user_octets_from_client{user="hello"} 28752101251 (26.78 GB)
telemt_user_octets_to_client{user="hello"} 547665441242 (510.05 GB)
telemt_user_msgs_from_client{user="hello"} 42816
telemt_user_msgs_to_client{user="hello"} 172415
telemt_user_unique_ips_current{user="hello"} 1143
telemt_user_unique_ips_recent_window{user="hello"} 585
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 147594.6 (40h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 13803166
telemt_connections_bad_total 1208651
telemt_connections_current 5473
telemt_connections_me_current 5473
telemt_handshake_timeouts_total 347905
telemt_upstream_connect_attempt_total 53560
telemt_upstream_connect_success_total 53478
telemt_upstream_connect_fail_total 8
telemt_upstream_connect_attempts_per_request{bucket="1"} 53486
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24217
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 29032
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 223
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 8
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 2433
telemt_me_reconnect_success_total 1276
telemt_me_reader_eof_total 1218
telemt_me_idle_close_by_peer_total 1217
telemt_me_route_drop_no_conn_total 12007171
telemt_me_route_drop_channel_closed_total 119
telemt_me_route_drop_queue_full_total 4
telemt_me_route_drop_queue_full_profile_total{profile="high"} 4
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 11071173
telemt_me_endpoint_quarantine_total 937
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 1097
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
telemt_me_writers_active_current 43
telemt_desync_total 44977
telemt_desync_full_logged_total 14286
telemt_desync_suppressed_total 30691
telemt_desync_frames_bucket_total{bucket="1_2"} 10186
telemt_desync_frames_bucket_total{bucket="3_10"} 17597
telemt_desync_frames_bucket_total{bucket="gt_10"} 17194
telemt_pool_swap_total 158
telemt_pool_force_close_total 5408
telemt_pool_stale_pick_total 19
telemt_me_writer_close_signal_drop_total 856
telemt_me_draining_writers_reap_progress_total 48856
telemt_me_writer_removed_unexpected_total 1175
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4245
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 45120
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 41
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4977
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 431
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 43448
telemt_me_writer_teardown_success_total{mode="normal"} 49365
telemt_me_writer_teardown_noop_total 48905
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89060
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 91982
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93425
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 95443
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 97741
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 98240
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 98270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 98270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 98270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 98270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 98270
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 98270
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 250.023321
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 98270
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 856
telemt_me_refill_failed_total 64
telemt_me_writer_restored_same_endpoint_total 1099
telemt_me_writer_restored_fallback_total 7
telemt_me_async_recovery_trigger_total 22
telemt_me_writer_removed_unexpected_minus_restored_total 69
telemt_user_connections_total{user="hello"} 11059168
telemt_user_connections_current{user="hello"} 5473
telemt_user_octets_from_client{user="hello"} 159379824388 (148.43 GB)
telemt_user_octets_to_client{user="hello"} 2950745225388 (2.68 TB)
telemt_user_unique_ips_current{user="hello"} 2211
telemt_user_unique_ips_recent_window{user="hello"} 839
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 147595.9 (40h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 10237841
telemt_connections_bad_total 956985
telemt_connections_current 5067
telemt_connections_me_current 5067
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 306701
telemt_upstream_connect_attempt_total 79946
telemt_upstream_connect_success_total 78808
telemt_upstream_connect_fail_total 817
telemt_upstream_connect_attempts_per_request{bucket="1"} 79625
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 43379
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 31594
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 157
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 3678
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 817
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 182
telemt_me_reconnect_attempts_total 3674
telemt_me_reconnect_success_total 1464
telemt_me_reader_eof_total 1337
telemt_me_idle_close_by_peer_total 1337
telemt_me_route_drop_no_conn_total 4085679
telemt_me_route_drop_channel_closed_total 433
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7644450
telemt_me_endpoint_quarantine_total 926
telemt_me_single_endpoint_outage_enter_total 24
telemt_me_single_endpoint_outage_exit_total 24
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 22
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1118
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 34176
telemt_desync_full_logged_total 11513
telemt_desync_suppressed_total 22663
telemt_desync_frames_bucket_total{bucket="1_2"} 8419
telemt_desync_frames_bucket_total{bucket="3_10"} 13150
telemt_desync_frames_bucket_total{bucket="gt_10"} 12607
telemt_pool_swap_total 157
telemt_pool_force_close_total 4830
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 602
telemt_me_draining_writers_reap_progress_total 47058
telemt_me_writer_removed_unexpected_total 1370
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4266
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44030
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4412
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 418
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42228
telemt_me_writer_teardown_success_total{mode="normal"} 48296
telemt_me_writer_teardown_noop_total 47073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 89686
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 92368
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 93360
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 94364
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 95027
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 95314
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 95359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 95361
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 95367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 95369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 95369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 95369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 95369
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 88.164444
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 95369
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 602
telemt_me_refill_failed_total 120
telemt_me_writer_restored_same_endpoint_total 1241
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 3
telemt_me_async_recovery_trigger_total 216
telemt_me_writer_removed_unexpected_minus_restored_total 115
telemt_user_connections_total{user="hello"} 7584163
telemt_user_connections_current{user="hello"} 5067
telemt_user_octets_from_client{user="hello"} 193573008529 (180.28 GB)
telemt_user_octets_to_client{user="hello"} 3427563913542 (3.12 TB)
telemt_user_msgs_from_client{user="hello"} 113340
telemt_user_msgs_to_client{user="hello"} 116189
telemt_user_unique_ips_current{user="hello"} 2127
telemt_user_unique_ips_recent_window{user="hello"} 731
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 147559.8 (40h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9706400
telemt_connections_bad_total 812575
telemt_connections_current 3526
telemt_connections_me_current 3526
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 314429
telemt_upstream_connect_attempt_total 65387
telemt_upstream_connect_success_total 64484
telemt_upstream_connect_fail_total 181
telemt_upstream_connect_attempts_per_request{bucket="1"} 64665
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 30984
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 30302
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1185
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2013
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 181
telemt_me_keepalive_timeout_total 1383
telemt_me_reconnect_attempts_total 4165
telemt_me_reconnect_success_total 1789
telemt_me_reader_eof_total 1558
telemt_me_idle_close_by_peer_total 1557
telemt_me_route_drop_no_conn_total 4811588
telemt_me_route_drop_channel_closed_total 326
telemt_me_route_drop_queue_full_total 9
telemt_me_route_drop_queue_full_profile_total{profile="high"} 9
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7324281
telemt_me_endpoint_quarantine_total 1015
telemt_me_single_endpoint_outage_enter_total 28
telemt_me_single_endpoint_outage_exit_total 28
telemt_me_single_endpoint_outage_reconnect_attempt_total 29
telemt_me_single_endpoint_outage_reconnect_success_total 23
telemt_me_single_endpoint_quarantine_bypass_total 29
telemt_me_single_endpoint_shadow_rotate_total 1080
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 54
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
telemt_desync_total 33948
telemt_desync_full_logged_total 11267
telemt_desync_suppressed_total 22681
telemt_desync_frames_bucket_total{bucket="1_2"} 8621
telemt_desync_frames_bucket_total{bucket="3_10"} 13014
telemt_desync_frames_bucket_total{bucket="gt_10"} 12313
telemt_pool_swap_total 153
telemt_pool_force_close_total 4775
telemt_pool_stale_pick_total 1619
telemt_me_writer_close_signal_drop_total 652
telemt_me_draining_writers_reap_progress_total 47709
telemt_me_writer_removed_unexpected_total 1705
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4760
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 44576
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 21
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 46
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4264
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 511
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 42934
telemt_me_writer_teardown_success_total{mode="normal"} 49336
telemt_me_writer_teardown_noop_total 47776
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 92172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 94500
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 95322
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 96247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 96729
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 96900
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 96985
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 97004
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 97012
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 97025
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 97058
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 97061
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 97112
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3153.665799
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 97112
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 652
telemt_me_refill_failed_total 122
telemt_me_writer_restored_same_endpoint_total 1563
telemt_me_writer_restored_fallback_total 7
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 56
telemt_me_writer_removed_unexpected_minus_restored_total 135
telemt_user_connections_total{user="hello"} 7318439
telemt_user_connections_current{user="hello"} 3526
telemt_user_octets_from_client{user="hello"} 171772999525 (159.98 GB)
telemt_user_octets_to_client{user="hello"} 3055907184933 (2.78 TB)
telemt_user_msgs_from_client{user="hello"} 46485
telemt_user_msgs_to_client{user="hello"} 113805
telemt_user_unique_ips_current{user="hello"} 1566
telemt_user_unique_ips_recent_window{user="hello"} 612
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 17840.3 (4h 57m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7524981
telemt_connections_bad_total 482594
telemt_connections_current 6958
telemt_connections_me_current 6958
telemt_relay_adaptive_promotions_total 8
telemt_relay_adaptive_hard_promotions_total 8
telemt_handshake_timeouts_total 119184
telemt_upstream_connect_attempt_total 27857
telemt_upstream_connect_success_total 26507
telemt_upstream_connect_fail_total 1010
telemt_upstream_connect_attempts_per_request{bucket="1"} 27517
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 14851
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 6409
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 543
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 4704
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1010
telemt_me_keepalive_timeout_total 679
telemt_me_reconnect_attempts_total 2638
telemt_me_reconnect_success_total 477
telemt_me_reader_eof_total 301
telemt_me_idle_close_by_peer_total 301
telemt_me_route_drop_no_conn_total 18213990
telemt_me_route_drop_channel_closed_total 27
telemt_me_route_drop_queue_full_total 25
telemt_me_route_drop_queue_full_profile_total{profile="high"} 25
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6257353
telemt_me_endpoint_quarantine_total 112
telemt_me_single_endpoint_outage_enter_total 32
telemt_me_single_endpoint_outage_exit_total 32
telemt_me_single_endpoint_outage_reconnect_attempt_total 57
telemt_me_single_endpoint_outage_reconnect_success_total 17
telemt_me_single_endpoint_quarantine_bypass_total 57
telemt_me_single_endpoint_shadow_rotate_total 140
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 12
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
telemt_desync_total 9164
telemt_desync_full_logged_total 2347
telemt_desync_suppressed_total 6817
telemt_desync_frames_bucket_total{bucket="1_2"} 1639
telemt_desync_frames_bucket_total{bucket="3_10"} 3734
telemt_desync_frames_bucket_total{bucket="gt_10"} 3791
telemt_pool_swap_total 16
telemt_pool_force_close_total 656
telemt_pool_stale_pick_total 1
telemt_me_writer_close_signal_drop_total 251
telemt_me_draining_writers_reap_progress_total 4652
telemt_me_writer_removed_unexpected_total 432
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 811
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 4231
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 474
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 182
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3996
telemt_me_writer_teardown_success_total{mode="normal"} 5042
telemt_me_writer_teardown_noop_total 4655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 7930
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8775
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 9129
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 9498
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 9635
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 9696
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 9697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 9697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 9697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 9697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 9697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 9697
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 9697
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 20.142250
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 9697
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 251
telemt_me_refill_failed_total 114
telemt_me_writer_restored_same_endpoint_total 319
telemt_me_writer_restored_fallback_total 3
telemt_me_async_recovery_trigger_total 204
telemt_me_writer_removed_unexpected_minus_restored_total 110
telemt_user_connections_total{user="hello"} 6272520
telemt_user_connections_current{user="hello"} 6958
telemt_user_octets_from_client{user="hello"} 34848962127 (32.46 GB)
telemt_user_octets_to_client{user="hello"} 184927453760 (172.23 GB)
telemt_user_msgs_from_client{user="hello"} 37295
telemt_user_msgs_to_client{user="hello"} 32778
telemt_user_unique_ips_current{user="hello"} 2589
telemt_user_unique_ips_recent_window{user="hello"} 1457
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 147566.7 (40h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9407949
telemt_connections_bad_total 781294
telemt_connections_current 4759
telemt_connections_me_current 4759
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 203268
telemt_upstream_connect_attempt_total 89685
telemt_upstream_connect_success_total 88785
telemt_upstream_connect_fail_total 778
telemt_upstream_connect_attempts_per_request{bucket="1"} 89563
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 55085
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 32240
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 208
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1252
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 778
telemt_me_keepalive_timeout_total 11
telemt_me_reconnect_attempts_total 71305
telemt_me_reconnect_success_total 2403
telemt_me_reader_eof_total 2137
telemt_me_idle_close_by_peer_total 2136
telemt_me_route_drop_no_conn_total 4571666
telemt_me_route_drop_channel_closed_total 19
telemt_me_route_drop_queue_full_total 46
telemt_me_route_drop_queue_full_profile_total{profile="high"} 46
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7428280
telemt_me_endpoint_quarantine_total 983
telemt_me_single_endpoint_outage_enter_total 31
telemt_me_single_endpoint_outage_exit_total 31
telemt_me_single_endpoint_outage_reconnect_attempt_total 33
telemt_me_single_endpoint_outage_reconnect_success_total 31
telemt_me_single_endpoint_quarantine_bypass_total 33
telemt_me_single_endpoint_shadow_rotate_total 1100
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 44
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
telemt_desync_total 38012
telemt_desync_full_logged_total 13000
telemt_desync_suppressed_total 25012
telemt_desync_frames_bucket_total{bucket="1_2"} 7708
telemt_desync_frames_bucket_total{bucket="3_10"} 14704
telemt_desync_frames_bucket_total{bucket="gt_10"} 15600
telemt_pool_swap_total 151
telemt_pool_force_close_total 4466
telemt_pool_stale_pick_total 69
telemt_me_writer_close_signal_drop_total 544
telemt_me_draining_writers_reap_progress_total 50354
telemt_me_writer_removed_unexpected_total 2165
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5308
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47227
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3854
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 612
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45888
telemt_me_writer_teardown_success_total{mode="normal"} 52535
telemt_me_writer_teardown_noop_total 50355
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 101094
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 102239
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 102585
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 102846
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 102880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 102883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 102883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 102886
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 102890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 102890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 102890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 102890
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 102890
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.563767
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 102890
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 544
telemt_me_refill_failed_total 4252
telemt_me_writer_restored_same_endpoint_total 2017
telemt_me_writer_restored_fallback_total 42
telemt_me_no_writer_failfast_total 228
telemt_me_async_recovery_trigger_total 7358
telemt_me_writer_removed_unexpected_minus_restored_total 106
telemt_user_connections_total{user="hello"} 7429719
telemt_user_connections_current{user="hello"} 4759
telemt_user_octets_from_client{user="hello"} 171732263735 (159.94 GB)
telemt_user_octets_to_client{user="hello"} 2833034817913 (2.58 TB)
telemt_user_msgs_from_client{user="hello"} 146235
telemt_user_msgs_to_client{user="hello"} 572261
telemt_user_unique_ips_current{user="hello"} 1930
telemt_user_unique_ips_recent_window{user="hello"} 657
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 84402.7 (23h 26m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9328360
telemt_connections_bad_total 332715
telemt_connections_current 4707
telemt_connections_me_current 4707
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 3925150
telemt_upstream_connect_attempt_total 41950
telemt_upstream_connect_success_total 41648
telemt_upstream_connect_fail_total 295
telemt_upstream_connect_attempts_per_request{bucket="1"} 41943
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 23858
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17676
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 114
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 295
telemt_me_reconnect_attempts_total 47904
telemt_me_reconnect_success_total 1435
telemt_me_reader_eof_total 1102
telemt_me_idle_close_by_peer_total 1102
telemt_me_route_drop_no_conn_total 3392046
telemt_me_route_drop_channel_closed_total 11
telemt_me_route_drop_queue_full_total 6
telemt_me_route_drop_queue_full_profile_total{profile="high"} 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4496513
telemt_me_endpoint_quarantine_total 554
telemt_me_single_endpoint_outage_enter_total 18
telemt_me_single_endpoint_outage_exit_total 18
telemt_me_single_endpoint_outage_reconnect_attempt_total 58
telemt_me_single_endpoint_outage_reconnect_success_total 18
telemt_me_single_endpoint_quarantine_bypass_total 58
telemt_me_single_endpoint_shadow_rotate_total 634
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 21
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
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 24605
telemt_desync_full_logged_total 8251
telemt_desync_suppressed_total 16354
telemt_desync_frames_bucket_total{bucket="1_2"} 4977
telemt_desync_frames_bucket_total{bucket="3_10"} 9708
telemt_desync_frames_bucket_total{bucket="gt_10"} 9920
telemt_pool_swap_total 88
telemt_pool_force_close_total 2739
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 284
telemt_me_draining_writers_reap_progress_total 29352
telemt_me_writer_removed_unexpected_total 1167
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2657
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 27890
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2333
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 406
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26613
telemt_me_writer_teardown_success_total{mode="normal"} 30547
telemt_me_writer_teardown_noop_total 29359
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 58918
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59466
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 59698
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 59906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 59906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 59906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 59906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 59906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 59906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 59906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 59906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 59906
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 59906
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.042593
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 59906
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 284
telemt_me_refill_failed_total 2701
telemt_me_writer_restored_same_endpoint_total 1282
telemt_me_writer_restored_fallback_total 14
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4328
telemt_user_connections_total{user="hello"} 4491261
telemt_user_connections_current{user="hello"} 4707
telemt_user_octets_from_client{user="hello"} 98894092284 (92.10 GB)
telemt_user_octets_to_client{user="hello"} 1723212322638 (1.57 TB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 1928
telemt_user_unique_ips_recent_window{user="hello"} 695
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 65373.5 (18h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 767594
telemt_connections_bad_total 9399
telemt_connections_current 1080
telemt_connections_me_current 1080
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 6
telemt_handshake_timeouts_total 14478
telemt_upstream_connect_attempt_total 33182
telemt_upstream_connect_success_total 33099
telemt_upstream_connect_fail_total 69
telemt_upstream_connect_attempts_per_request{bucket="1"} 33168
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15183
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17507
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 409
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 69
telemt_me_reconnect_attempts_total 1460
telemt_me_reconnect_success_total 628
telemt_me_reader_eof_total 610
telemt_me_idle_close_by_peer_total 610
telemt_me_route_drop_no_conn_total 258251
telemt_me_route_drop_channel_closed_total 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 689556
telemt_me_endpoint_quarantine_total 584
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 547
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 13
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
telemt_me_writers_active_current 45
telemt_desync_total 3817
telemt_desync_full_logged_total 1139
telemt_desync_suppressed_total 2678
telemt_desync_frames_bucket_total{bucket="1_2"} 934
telemt_desync_frames_bucket_total{bucket="3_10"} 1520
telemt_desync_frames_bucket_total{bucket="gt_10"} 1363
telemt_pool_swap_total 69
telemt_pool_force_close_total 1707
telemt_me_writer_close_signal_drop_total 98
telemt_me_draining_writers_reap_progress_total 27262
telemt_me_writer_removed_unexpected_total 590
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2084
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25790
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1630
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 77
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25555
telemt_me_writer_teardown_success_total{mode="normal"} 27874
telemt_me_writer_teardown_noop_total 27264
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 54583
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55113
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55138
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.009753
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55138
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 98
telemt_me_refill_failed_total 45
telemt_me_writer_restored_same_endpoint_total 545
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 28
telemt_me_writer_removed_unexpected_minus_restored_total 36
telemt_user_connections_total{user="hello"} 691050
telemt_user_connections_current{user="hello"} 1080
telemt_user_octets_from_client{user="hello"} 13014247609 (12.12 GB)
telemt_user_octets_to_client{user="hello"} 326855366403 (304.41 GB)
telemt_user_msgs_from_client{user="hello"} 18894
telemt_user_msgs_to_client{user="hello"} 38815
telemt_user_unique_ips_current{user="hello"} 401
telemt_user_unique_ips_recent_window{user="hello"} 156
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 147571.5 (40h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 11492727
telemt_connections_bad_total 1347053
telemt_connections_current 6254
telemt_connections_me_current 6254
telemt_handshake_timeouts_total 311925
telemt_upstream_connect_attempt_total 55680
telemt_upstream_connect_success_total 55465
telemt_upstream_connect_fail_total 167
telemt_upstream_connect_attempts_per_request{bucket="1"} 55632
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 27340
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 28078
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 46
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 167
telemt_me_reconnect_attempts_total 2187
telemt_me_reconnect_success_total 1163
telemt_me_reader_eof_total 1128
telemt_me_idle_close_by_peer_total 1128
telemt_me_route_drop_no_conn_total 3634107
telemt_me_route_drop_channel_closed_total 98
telemt_me_route_drop_queue_full_total 32
telemt_me_route_drop_queue_full_profile_total{profile="high"} 32
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 8631457
telemt_me_endpoint_quarantine_total 1011
telemt_me_single_endpoint_outage_enter_total 11
telemt_me_single_endpoint_outage_exit_total 11
telemt_me_single_endpoint_outage_reconnect_attempt_total 12
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 12
telemt_me_single_endpoint_shadow_rotate_total 1105
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 40
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
telemt_desync_total 35387
telemt_desync_full_logged_total 11609
telemt_desync_suppressed_total 23778
telemt_desync_frames_bucket_total{bucket="1_2"} 8434
telemt_desync_frames_bucket_total{bucket="3_10"} 13120
telemt_desync_frames_bucket_total{bucket="gt_10"} 13833
telemt_pool_swap_total 163
telemt_pool_force_close_total 4477
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 563
telemt_me_draining_writers_reap_progress_total 50153
telemt_me_writer_removed_unexpected_total 1083
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4109
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 47163
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 4324
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 153
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45676
telemt_me_writer_teardown_success_total{mode="normal"} 51272
telemt_me_writer_teardown_noop_total 50155
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 99354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100764
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 101041
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 101321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 101423
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 101427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 101427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 101427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 101427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 101427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 101427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 101427
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 101427
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.138939
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 101427
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 563
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 1019
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 44
telemt_me_writer_removed_unexpected_minus_restored_total 53
telemt_user_connections_total{user="hello"} 8602096
telemt_user_connections_current{user="hello"} 6254
telemt_user_octets_from_client{user="hello"} 166402922728 (154.97 GB)
telemt_user_octets_to_client{user="hello"} 3875082489704 (3.52 TB)
telemt_user_unique_ips_current{user="hello"} 2292
telemt_user_unique_ips_recent_window{user="hello"} 781
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 147568.0 (40h 59m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 9914533
telemt_connections_bad_total 1108975
telemt_connections_current 4532
telemt_connections_me_current 4532
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 259635
telemt_upstream_connect_attempt_total 81242
telemt_upstream_connect_success_total 80649
telemt_upstream_connect_fail_total 513
telemt_upstream_connect_attempts_per_request{bucket="1"} 81162
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 44623
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 33109
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 909
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 2008
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 513
telemt_me_reconnect_attempts_total 8561
telemt_me_reconnect_success_total 1927
telemt_me_reader_eof_total 1797
telemt_me_idle_close_by_peer_total 1797
telemt_me_seq_mismatch_total 71
telemt_me_route_drop_no_conn_total 4444608
telemt_me_route_drop_channel_closed_total 317
telemt_me_route_drop_queue_full_total 16
telemt_me_route_drop_queue_full_profile_total{profile="high"} 16
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 7631833
telemt_me_endpoint_quarantine_total 1126
telemt_me_hardswap_pending_ttl_expired_total 1
telemt_me_single_endpoint_outage_enter_total 37
telemt_me_single_endpoint_outage_exit_total 37
telemt_me_single_endpoint_outage_reconnect_attempt_total 37
telemt_me_single_endpoint_outage_reconnect_success_total 35
telemt_me_single_endpoint_quarantine_bypass_total 37
telemt_me_single_endpoint_shadow_rotate_total 1108
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 45
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
telemt_desync_total 34599
telemt_desync_full_logged_total 11269
telemt_desync_suppressed_total 23330
telemt_desync_frames_bucket_total{bucket="1_2"} 8546
telemt_desync_frames_bucket_total{bucket="3_10"} 12887
telemt_desync_frames_bucket_total{bucket="gt_10"} 13166
telemt_pool_swap_total 156
telemt_pool_force_close_total 4339
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 555
telemt_me_draining_writers_reap_progress_total 49492
telemt_me_writer_removed_unexpected_total 1821
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 5124
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 46256
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3945
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 394
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 45153
telemt_me_writer_teardown_success_total{mode="normal"} 51380
telemt_me_writer_teardown_noop_total 49496
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 98556
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 100073
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 100554
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 100826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 100876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 100876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 100876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 100876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 100876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 100876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 100876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 100876
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 100876
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 15.233062
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 100876
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 555
telemt_me_refill_failed_total 340
telemt_me_writer_restored_same_endpoint_total 1567
telemt_me_writer_restored_fallback_total 95
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 128
telemt_me_writer_removed_unexpected_minus_restored_total 159
telemt_user_connections_total{user="hello"} 7638984
telemt_user_connections_current{user="hello"} 4532
telemt_user_octets_from_client{user="hello"} 135160317129 (125.88 GB)
telemt_user_octets_to_client{user="hello"} 3014080480003 (2.74 TB)
telemt_user_msgs_from_client{user="hello"} 100726
telemt_user_msgs_to_client{user="hello"} 247529
telemt_user_unique_ips_current{user="hello"} 1882
telemt_user_unique_ips_recent_window{user="hello"} 695
```