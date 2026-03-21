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

# Server Metrics 2026-03-21 19:42:47 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 83213.7 (23h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3004650
telemt_connections_bad_total 175569
telemt_connections_current 1101
telemt_connections_me_current 1101
telemt_relay_adaptive_promotions_total 3
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 91659
telemt_upstream_connect_attempt_total 34098
telemt_upstream_connect_success_total 33955
telemt_upstream_connect_fail_total 100
telemt_upstream_connect_attempts_per_request{bucket="1"} 34055
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13762
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20073
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 53
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 67
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 100
telemt_me_keepalive_failed_total 3
telemt_me_keepalive_timeout_total 99
telemt_me_reconnect_attempts_total 1855
telemt_me_reconnect_success_total 745
telemt_me_reader_eof_total 713
telemt_me_idle_close_by_peer_total 713
telemt_me_route_drop_no_conn_total 2600670
telemt_me_route_drop_channel_closed_total 833
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 2428558
telemt_me_writer_pick_total{mode="p2c",result="full"} 26
telemt_me_endpoint_quarantine_total 563
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 10
telemt_me_single_endpoint_outage_reconnect_success_total 9
telemt_me_single_endpoint_quarantine_bypass_total 10
telemt_me_single_endpoint_shadow_rotate_total 649
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_me_writers_active_current 46
telemt_desync_total 9632
telemt_desync_full_logged_total 3376
telemt_desync_suppressed_total 6256
telemt_desync_frames_bucket_total{bucket="1_2"} 2103
telemt_desync_frames_bucket_total{bucket="3_10"} 3650
telemt_desync_frames_bucket_total{bucket="gt_10"} 3879
telemt_pool_swap_total 90
telemt_pool_force_close_total 2737
telemt_pool_stale_pick_total 31
telemt_me_writer_close_signal_drop_total 628
telemt_me_draining_writers_reap_progress_total 27866
telemt_me_writer_removed_unexpected_total 695
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2355
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25948
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 8
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2598
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 139
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25129
telemt_me_writer_teardown_success_total{mode="normal"} 28303
telemt_me_writer_teardown_noop_total 27874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 45849
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 47718
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 49333
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52243
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54639
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55807
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56147
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56172
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56177
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56177
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 292.560920
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56177
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 628
telemt_me_refill_failed_total 61
telemt_me_writer_restored_same_endpoint_total 639
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 12
telemt_me_writer_removed_unexpected_minus_restored_total 48
telemt_user_connections_total{user="hello"} 2428273
telemt_user_connections_current{user="hello"} 1101
telemt_user_octets_from_client{user="hello"} 35983773141 (33.51 GB)
telemt_user_octets_to_client{user="hello"} 606758311570 (565.09 GB)
telemt_user_msgs_from_client{user="hello"} 7227
telemt_user_msgs_to_client{user="hello"} 6949
telemt_user_unique_ips_current{user="hello"} 452
telemt_user_unique_ips_recent_window{user="hello"} 151
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 8351.7 (2h 19m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 353953
telemt_connections_bad_total 14963
telemt_connections_current 902
telemt_connections_me_current 902
telemt_handshake_timeouts_total 11643
telemt_upstream_connect_attempt_total 3354
telemt_upstream_connect_success_total 3275
telemt_upstream_connect_fail_total 67
telemt_upstream_connect_attempts_per_request{bucket="1"} 3342
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1427
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 1837
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 67
telemt_me_reconnect_attempts_total 161
telemt_me_reconnect_success_total 117
telemt_me_reader_eof_total 92
telemt_me_idle_close_by_peer_total 92
telemt_me_route_drop_no_conn_total 235717
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 292734
telemt_me_endpoint_quarantine_total 75
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 71
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 9
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
telemt_desync_total 1233
telemt_desync_full_logged_total 705
telemt_desync_suppressed_total 528
telemt_desync_frames_bucket_total{bucket="1_2"} 242
telemt_desync_frames_bucket_total{bucket="3_10"} 458
telemt_desync_frames_bucket_total{bucket="gt_10"} 533
telemt_pool_swap_total 9
telemt_pool_force_close_total 280
telemt_me_writer_close_signal_drop_total 30
telemt_me_draining_writers_reap_progress_total 2881
telemt_me_writer_removed_unexpected_total 87
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 260
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 2700
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 273
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 2601
telemt_me_writer_teardown_success_total{mode="normal"} 2960
telemt_me_writer_teardown_noop_total 2881
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 5615
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 5765
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 5794
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 5841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 5841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 5841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 5841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 5841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 5841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 5841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 5841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 5841
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 5841
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.393235
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 5841
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 30
telemt_me_refill_failed_total 2
telemt_me_writer_restored_same_endpoint_total 77
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 4
telemt_me_writer_removed_unexpected_minus_restored_total 5
telemt_user_connections_total{user="hello"} 292389
telemt_user_connections_current{user="hello"} 902
telemt_user_octets_from_client{user="hello"} 4869912928 (4.54 GB)
telemt_user_octets_to_client{user="hello"} 80625197648 (75.09 GB)
telemt_user_unique_ips_current{user="hello"} 544
telemt_user_unique_ips_recent_window{user="hello"} 460
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 83211.6 (23h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6570385
telemt_connections_bad_total 507181
telemt_connections_current 3638
telemt_connections_me_current 3638
telemt_handshake_timeouts_total 208392
telemt_upstream_connect_attempt_total 29975
telemt_upstream_connect_success_total 29915
telemt_upstream_connect_fail_total 6
telemt_upstream_connect_attempts_per_request{bucket="1"} 29921
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 13460
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16325
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 124
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 6
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1255
telemt_me_reconnect_success_total 652
telemt_me_reader_eof_total 661
telemt_me_idle_close_by_peer_total 661
telemt_me_route_drop_no_conn_total 4187109
telemt_me_route_drop_channel_closed_total 59
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5413313
telemt_me_endpoint_quarantine_total 516
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 620
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 19
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
telemt_desync_total 21987
telemt_desync_full_logged_total 7348
telemt_desync_suppressed_total 14639
telemt_desync_frames_bucket_total{bucket="1_2"} 4619
telemt_desync_frames_bucket_total{bucket="3_10"} 8759
telemt_desync_frames_bucket_total{bucket="gt_10"} 8609
telemt_pool_swap_total 89
telemt_pool_force_close_total 2987
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 486
telemt_me_draining_writers_reap_progress_total 27284
telemt_me_writer_removed_unexpected_total 636
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2364
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25206
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 37
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2757
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 230
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24297
telemt_me_writer_teardown_success_total{mode="normal"} 27570
telemt_me_writer_teardown_noop_total 27321
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 49847
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 52248
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 53412
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 54176
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 54633
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 54880
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 54891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 54891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 54891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 54891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 54891
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 54891
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 129.154104
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 54891
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 486
telemt_me_refill_failed_total 31
telemt_me_writer_restored_same_endpoint_total 588
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 5406769
telemt_user_connections_current{user="hello"} 3638
telemt_user_octets_from_client{user="hello"} 90544270596 (84.33 GB)
telemt_user_octets_to_client{user="hello"} 1687328765168 (1.53 TB)
telemt_user_unique_ips_current{user="hello"} 1501
telemt_user_unique_ips_recent_window{user="hello"} 599
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 83213.1 (23h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5312172
telemt_connections_bad_total 497940
telemt_connections_current 3606
telemt_connections_me_current 3606
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 175387
telemt_upstream_connect_attempt_total 34197
telemt_upstream_connect_success_total 33884
telemt_upstream_connect_fail_total 159
telemt_upstream_connect_attempts_per_request{bucket="1"} 34043
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 17170
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 16147
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 27
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 540
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 159
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1624
telemt_me_reconnect_success_total 683
telemt_me_reader_eof_total 654
telemt_me_idle_close_by_peer_total 654
telemt_me_route_drop_no_conn_total 1848764
telemt_me_route_drop_channel_closed_total 207
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3985354
telemt_me_endpoint_quarantine_total 515
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 635
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 26
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
telemt_desync_total 18643
telemt_desync_full_logged_total 6188
telemt_desync_suppressed_total 12455
telemt_desync_frames_bucket_total{bucket="1_2"} 4517
telemt_desync_frames_bucket_total{bucket="3_10"} 7224
telemt_desync_frames_bucket_total{bucket="gt_10"} 6902
telemt_pool_swap_total 91
telemt_pool_force_close_total 2754
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 307
telemt_me_draining_writers_reap_progress_total 26174
telemt_me_writer_removed_unexpected_total 634
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2280
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 24456
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 5
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2568
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 186
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 23420
telemt_me_writer_teardown_success_total{mode="normal"} 26736
telemt_me_writer_teardown_noop_total 26179
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 50114
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 51451
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 51921
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 52426
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52766
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52902
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52915
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 38.945006
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52915
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 307
telemt_me_refill_failed_total 50
telemt_me_writer_restored_same_endpoint_total 583
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 43
telemt_user_connections_total{user="hello"} 3982522
telemt_user_connections_current{user="hello"} 3606
telemt_user_octets_from_client{user="hello"} 117849701385 (109.76 GB)
telemt_user_octets_to_client{user="hello"} 1803176496691 (1.64 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 1424
telemt_user_unique_ips_recent_window{user="hello"} 442
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 83176.9 (23h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5245340
telemt_connections_bad_total 471955
telemt_connections_current 3475
telemt_connections_me_current 3475
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 158220
telemt_upstream_connect_attempt_total 40555
telemt_upstream_connect_success_total 40291
telemt_upstream_connect_fail_total 134
telemt_upstream_connect_attempts_per_request{bucket="1"} 40425
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 21355
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17577
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 327
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1032
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 134
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1701
telemt_me_reconnect_success_total 737
telemt_me_reader_eof_total 681
telemt_me_idle_close_by_peer_total 681
telemt_me_route_drop_no_conn_total 1908282
telemt_me_route_drop_channel_closed_total 93
telemt_me_route_drop_queue_full_total 3
telemt_me_route_drop_queue_full_profile_total{profile="high"} 3
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 3963729
telemt_me_endpoint_quarantine_total 564
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 623
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
telemt_me_writers_active_current 44
telemt_desync_total 18479
telemt_desync_full_logged_total 6008
telemt_desync_suppressed_total 12471
telemt_desync_frames_bucket_total{bucket="1_2"} 4589
telemt_desync_frames_bucket_total{bucket="3_10"} 7006
telemt_desync_frames_bucket_total{bucket="gt_10"} 6884
telemt_pool_swap_total 89
telemt_pool_force_close_total 2622
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 321
telemt_me_draining_writers_reap_progress_total 27571
telemt_me_writer_removed_unexpected_total 650
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2358
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25884
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2414
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 208
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 24949
telemt_me_writer_teardown_success_total{mode="normal"} 28242
telemt_me_writer_teardown_noop_total 27581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 53750
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 54887
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 55237
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 55636
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 55800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 55820
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 55823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 55823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 55823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 55823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 55823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 55823
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 55823
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 19.906064
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 55823
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 321
telemt_me_refill_failed_total 53
telemt_me_writer_restored_same_endpoint_total 633
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 13
telemt_user_connections_total{user="hello"} 3966405
telemt_user_connections_current{user="hello"} 3475
telemt_user_octets_from_client{user="hello"} 114571308583 (106.70 GB)
telemt_user_octets_to_client{user="hello"} 1805310536067 (1.64 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 1336
telemt_user_unique_ips_recent_window{user="hello"} 482
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 83216.2 (23h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 18282261
telemt_connections_bad_total 1150490
telemt_connections_current 4767
telemt_connections_me_current 4767
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 513176
telemt_upstream_connect_attempt_total 173641
telemt_upstream_connect_success_total 156789
telemt_upstream_connect_fail_total 15492
telemt_upstream_connect_attempts_per_request{bucket="1"} 172281
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 111892
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 35058
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1024
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8815
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 15492
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 4591
telemt_me_reconnect_success_total 1717
telemt_me_reader_eof_total 1174
telemt_me_idle_close_by_peer_total 1173
telemt_me_route_drop_no_conn_total 37349179
telemt_me_route_drop_channel_closed_total 108
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 15066957
telemt_me_endpoint_quarantine_total 613
telemt_me_single_endpoint_outage_enter_total 98
telemt_me_single_endpoint_outage_exit_total 98
telemt_me_single_endpoint_outage_reconnect_attempt_total 216
telemt_me_single_endpoint_outage_reconnect_success_total 47
telemt_me_single_endpoint_quarantine_bypass_total 216
telemt_me_single_endpoint_shadow_rotate_total 646
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 49
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
telemt_desync_total 27529
telemt_desync_full_logged_total 8190
telemt_desync_suppressed_total 19339
telemt_desync_frames_bucket_total{bucket="1_2"} 5882
telemt_desync_frames_bucket_total{bucket="3_10"} 12296
telemt_desync_frames_bucket_total{bucket="gt_10"} 9351
telemt_pool_swap_total 85
telemt_pool_force_close_total 2826
telemt_pool_stale_pick_total 5
telemt_me_writer_close_signal_drop_total 636
telemt_me_draining_writers_reap_progress_total 25744
telemt_me_writer_removed_unexpected_total 1626
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3449
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 23679
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 15
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2383
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 443
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 22918
telemt_me_writer_teardown_success_total{mode="normal"} 27128
telemt_me_writer_teardown_noop_total 25760
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 47256
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 49273
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 50390
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 51715
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 52503
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 52800
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 52869
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 52871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 52874
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 52879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 52879
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 52883
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 52888
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 196.829149
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 52888
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 636
telemt_me_refill_failed_total 98
telemt_me_writer_restored_same_endpoint_total 1188
telemt_me_writer_restored_fallback_total 11
telemt_me_async_recovery_trigger_total 160
telemt_me_writer_removed_unexpected_minus_restored_total 427
telemt_user_connections_total{user="hello"} 15185909
telemt_user_connections_current{user="hello"} 4767
telemt_user_octets_from_client{user="hello"} 136826504423 (127.43 GB)
telemt_user_octets_to_client{user="hello"} 935622604531 (871.37 GB)
telemt_user_msgs_from_client{user="hello"} 352315
telemt_user_msgs_to_client{user="hello"} 633668
telemt_user_unique_ips_current{user="hello"} 1766
telemt_user_unique_ips_recent_window{user="hello"} 780
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 83183.8 (23h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5201228
telemt_connections_bad_total 508425
telemt_connections_current 3749
telemt_connections_me_current 3749
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 106856
telemt_upstream_connect_attempt_total 43618
telemt_upstream_connect_success_total 43162
telemt_upstream_connect_fail_total 375
telemt_upstream_connect_attempts_per_request{bucket="1"} 43537
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 25061
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17776
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 324
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 375
telemt_me_reconnect_attempts_total 3415
telemt_me_reconnect_success_total 1203
telemt_me_reader_eof_total 1176
telemt_me_idle_close_by_peer_total 1176
telemt_me_route_drop_no_conn_total 2196405
telemt_me_route_drop_channel_closed_total 9
telemt_me_route_drop_queue_full_total 36
telemt_me_route_drop_queue_full_profile_total{profile="high"} 36
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4022765
telemt_me_endpoint_quarantine_total 501
telemt_me_single_endpoint_outage_enter_total 13
telemt_me_single_endpoint_outage_exit_total 13
telemt_me_single_endpoint_outage_reconnect_attempt_total 13
telemt_me_single_endpoint_outage_reconnect_success_total 13
telemt_me_single_endpoint_quarantine_bypass_total 13
telemt_me_single_endpoint_shadow_rotate_total 618
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
telemt_me_writers_active_current 44
telemt_desync_total 19838
telemt_desync_full_logged_total 6872
telemt_desync_suppressed_total 12966
telemt_desync_frames_bucket_total{bucket="1_2"} 3817
telemt_desync_frames_bucket_total{bucket="3_10"} 7782
telemt_desync_frames_bucket_total{bucket="gt_10"} 8239
telemt_pool_swap_total 84
telemt_pool_force_close_total 2468
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 305
telemt_me_draining_writers_reap_progress_total 28353
telemt_me_writer_removed_unexpected_total 1140
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2884
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26620
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2127
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 341
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25885
telemt_me_writer_teardown_success_total{mode="normal"} 29504
telemt_me_writer_teardown_noop_total 28354
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56868
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57513
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57735
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57826
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57855
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57858
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 6.661531
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57858
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 305
telemt_me_refill_failed_total 119
telemt_me_writer_restored_same_endpoint_total 1023
telemt_me_writer_restored_fallback_total 15
telemt_me_async_recovery_trigger_total 48
telemt_me_writer_removed_unexpected_minus_restored_total 102
telemt_user_connections_total{user="hello"} 4013284
telemt_user_connections_current{user="hello"} 3749
telemt_user_octets_from_client{user="hello"} 107430538349 (100.05 GB)
telemt_user_octets_to_client{user="hello"} 1615665737963 (1.47 TB)
telemt_user_msgs_from_client{user="hello"} 59697
telemt_user_msgs_to_client{user="hello"} 266554
telemt_user_unique_ips_current{user="hello"} 1503
telemt_user_unique_ips_recent_window{user="hello"} 817
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 20019.7 (5h 33m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 2773866
telemt_connections_bad_total 105431
telemt_connections_current 2713
telemt_connections_me_current 2713
telemt_handshake_timeouts_total 1192192
telemt_upstream_connect_attempt_total 6452
telemt_upstream_connect_success_total 6356
telemt_upstream_connect_fail_total 90
telemt_upstream_connect_attempts_per_request{bucket="1"} 6446
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 2800
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 3512
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 44
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 90
telemt_me_reconnect_attempts_total 647
telemt_me_reconnect_success_total 198
telemt_me_reader_eof_total 183
telemt_me_idle_close_by_peer_total 183
telemt_me_route_drop_no_conn_total 844697
telemt_me_route_drop_channel_closed_total 2
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1312090
telemt_me_endpoint_quarantine_total 98
telemt_me_single_endpoint_outage_enter_total 4
telemt_me_single_endpoint_outage_exit_total 4
telemt_me_single_endpoint_outage_reconnect_attempt_total 4
telemt_me_single_endpoint_outage_reconnect_success_total 4
telemt_me_single_endpoint_quarantine_bypass_total 4
telemt_me_single_endpoint_shadow_rotate_total 149
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 2
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
telemt_desync_total 7176
telemt_desync_full_logged_total 2356
telemt_desync_suppressed_total 4820
telemt_desync_frames_bucket_total{bucket="1_2"} 1303
telemt_desync_frames_bucket_total{bucket="3_10"} 2692
telemt_desync_frames_bucket_total{bucket="gt_10"} 3181
telemt_pool_swap_total 21
telemt_pool_force_close_total 676
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 67
telemt_me_draining_writers_reap_progress_total 5594
telemt_me_writer_removed_unexpected_total 180
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 542
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 5237
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 590
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 86
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 4918
telemt_me_writer_teardown_success_total{mode="normal"} 5779
telemt_me_writer_teardown_noop_total 5594
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 11133
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 11258
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 11297
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 11373
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 11373
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 1.899471
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 11373
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 67
telemt_me_refill_failed_total 26
telemt_me_writer_restored_same_endpoint_total 164
telemt_me_async_recovery_trigger_total 6
telemt_me_writer_removed_unexpected_minus_restored_total 16
telemt_user_connections_total{user="hello"} 1308541
telemt_user_connections_current{user="hello"} 2713
telemt_user_octets_from_client{user="hello"} 39909289716 (37.17 GB)
telemt_user_octets_to_client{user="hello"} 522606140012 (486.71 GB)
telemt_user_unique_ips_current{user="hello"} 1065
telemt_user_unique_ips_recent_window{user="hello"} 1018
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 990.7 (0h 16m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7297
telemt_connections_bad_total 9
telemt_connections_current 651
telemt_connections_me_current 651
telemt_handshake_timeouts_total 173
telemt_upstream_connect_attempt_total 487
telemt_upstream_connect_success_total 486
telemt_upstream_connect_fail_total 1
telemt_upstream_connect_attempts_per_request{bucket="1"} 487
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 198
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 277
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 11
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 1
telemt_me_reconnect_attempts_total 5
telemt_me_reconnect_success_total 5
telemt_me_reader_eof_total 5
telemt_me_idle_close_by_peer_total 5
telemt_me_route_drop_no_conn_total 1894
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6797
telemt_me_endpoint_quarantine_total 6
telemt_me_single_endpoint_shadow_rotate_total 13
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 1
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
telemt_me_writers_warm_current 39
telemt_desync_total 23
telemt_desync_full_logged_total 8
telemt_desync_suppressed_total 15
telemt_desync_frames_bucket_total{bucket="1_2"} 2
telemt_desync_frames_bucket_total{bucket="3_10"} 14
telemt_desync_frames_bucket_total{bucket="gt_10"} 7
telemt_me_draining_writers_reap_progress_total 327
telemt_me_writer_removed_unexpected_total 5
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 10
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 327
telemt_me_writer_teardown_success_total{mode="normal"} 332
telemt_me_writer_teardown_noop_total 327
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 659
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 659
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.008070
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 659
telemt_me_writer_restored_same_endpoint_total 5
telemt_user_connections_total{user="hello"} 6797
telemt_user_connections_current{user="hello"} 651
telemt_user_octets_from_client{user="hello"} 386067088 (368.18 MB)
telemt_user_octets_to_client{user="hello"} 6926789800 (6.45 GB)
telemt_user_unique_ips_current{user="hello"} 237
telemt_user_unique_ips_recent_window{user="hello"} 107
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 83188.2 (23h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6055584
telemt_connections_bad_total 572619
telemt_connections_current 4153
telemt_connections_me_current 4153
telemt_handshake_timeouts_total 181037
telemt_upstream_connect_attempt_total 31783
telemt_upstream_connect_success_total 31656
telemt_upstream_connect_fail_total 91
telemt_upstream_connect_attempts_per_request{bucket="1"} 31747
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15673
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 15945
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 37
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 91
telemt_me_reconnect_attempts_total 1352
telemt_me_reconnect_success_total 691
telemt_me_reader_eof_total 663
telemt_me_idle_close_by_peer_total 663
telemt_me_route_drop_no_conn_total 1906166
telemt_me_route_drop_channel_closed_total 51
telemt_me_route_drop_queue_full_total 21
telemt_me_route_drop_queue_full_profile_total{profile="high"} 21
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4704733
telemt_me_endpoint_quarantine_total 557
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 635
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
telemt_me_writers_active_current 44
telemt_desync_total 17807
telemt_desync_full_logged_total 5886
telemt_desync_suppressed_total 11921
telemt_desync_frames_bucket_total{bucket="1_2"} 4346
telemt_desync_frames_bucket_total{bucket="3_10"} 6520
telemt_desync_frames_bucket_total{bucket="gt_10"} 6941
telemt_pool_swap_total 92
telemt_pool_force_close_total 2498
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 314
telemt_me_draining_writers_reap_progress_total 28529
telemt_me_writer_removed_unexpected_total 648
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2323
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 26859
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2428
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 70
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 26031
telemt_me_writer_teardown_success_total{mode="normal"} 29182
telemt_me_writer_teardown_noop_total 28530
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 56586
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 57310
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 57450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 57624
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 57712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 57712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 57712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 57712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 57712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 57712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 57712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 57712
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 57712
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.288401
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 57712
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 314
telemt_me_refill_failed_total 34
telemt_me_writer_restored_same_endpoint_total 617
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 26
telemt_user_connections_total{user="hello"} 4681154
telemt_user_connections_current{user="hello"} 4153
telemt_user_octets_from_client{user="hello"} 91442275832 (85.16 GB)
telemt_user_octets_to_client{user="hello"} 2167279670256 (1.97 TB)
telemt_user_unique_ips_current{user="hello"} 1460
telemt_user_unique_ips_recent_window{user="hello"} 494
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 83185.0 (23h 6m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5145667
telemt_connections_bad_total 453042
telemt_connections_current 3730
telemt_connections_me_current 3730
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 151175
telemt_upstream_connect_attempt_total 48166
telemt_upstream_connect_success_total 47812
telemt_upstream_connect_fail_total 295
telemt_upstream_connect_attempts_per_request{bucket="1"} 48107
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 28900
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 17781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 613
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 295
telemt_me_reconnect_attempts_total 4429
telemt_me_reconnect_success_total 972
telemt_me_reader_eof_total 861
telemt_me_idle_close_by_peer_total 861
telemt_me_seq_mismatch_total 35
telemt_me_route_drop_no_conn_total 1963241
telemt_me_route_drop_channel_closed_total 179
telemt_me_route_drop_queue_full_total 10
telemt_me_route_drop_queue_full_profile_total{profile="high"} 10
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4098158
telemt_me_endpoint_quarantine_total 666
telemt_me_single_endpoint_outage_enter_total 25
telemt_me_single_endpoint_outage_exit_total 25
telemt_me_single_endpoint_outage_reconnect_attempt_total 25
telemt_me_single_endpoint_outage_reconnect_success_total 24
telemt_me_single_endpoint_quarantine_bypass_total 25
telemt_me_single_endpoint_shadow_rotate_total 634
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 28
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
telemt_desync_total 16278
telemt_desync_full_logged_total 5508
telemt_desync_suppressed_total 10770
telemt_desync_frames_bucket_total{bucket="1_2"} 4013
telemt_desync_frames_bucket_total{bucket="3_10"} 6023
telemt_desync_frames_bucket_total{bucket="gt_10"} 6242
telemt_pool_swap_total 90
telemt_pool_force_close_total 2433
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 308
telemt_me_draining_writers_reap_progress_total 27759
telemt_me_writer_removed_unexpected_total 872
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2775
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 25894
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2242
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 191
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 25326
telemt_me_writer_teardown_success_total{mode="normal"} 28669
telemt_me_writer_teardown_noop_total 27761
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 55106
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 55963
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 56221
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 56398
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 56430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 56430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 56430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 56430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 56430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 56430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 56430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 56430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 56430
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 9.130832
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 56430
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 308
telemt_me_refill_failed_total 197
telemt_me_writer_restored_same_endpoint_total 751
telemt_me_writer_restored_fallback_total 45
telemt_me_async_recovery_trigger_total 59
telemt_me_writer_removed_unexpected_minus_restored_total 76
telemt_user_connections_total{user="hello"} 4103142
telemt_user_connections_current{user="hello"} 3730
telemt_user_octets_from_client{user="hello"} 76118449781 (70.89 GB)
telemt_user_octets_to_client{user="hello"} 1708506697564 (1.55 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 1456
telemt_user_unique_ips_recent_window{user="hello"} 472
```