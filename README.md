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

# Server Metrics 2026-03-22 00:18:16 UTC
- Updated every 5 minutes. 
- Metrics with a value of 0 are not displayed.

## NKtelecom

```
telemt 3.3.28

telemt_uptime_seconds 11514.3 (3h 11m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 176297
telemt_connections_bad_total 11820
telemt_connections_current 618
telemt_connections_me_current 618
telemt_handshake_timeouts_total 9814
telemt_upstream_connect_attempt_total 4672
telemt_upstream_connect_success_total 4671
telemt_upstream_connect_attempts_per_request{bucket="1"} 4671
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 1733
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 2924
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 4
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 10
telemt_me_reconnect_attempts_total 144
telemt_me_reconnect_success_total 72
telemt_me_reader_eof_total 73
telemt_me_idle_close_by_peer_total 73
telemt_me_route_drop_no_conn_total 35803
telemt_me_route_drop_channel_closed_total 6
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144515
telemt_me_endpoint_quarantine_total 74
telemt_me_single_endpoint_shadow_rotate_total 97
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
telemt_desync_total 988
telemt_desync_full_logged_total 288
telemt_desync_suppressed_total 700
telemt_desync_frames_bucket_total{bucket="1_2"} 247
telemt_desync_frames_bucket_total{bucket="3_10"} 327
telemt_desync_frames_bucket_total{bucket="gt_10"} 414
telemt_pool_swap_total 12
telemt_pool_force_close_total 326
telemt_me_writer_close_signal_drop_total 22
telemt_me_draining_writers_reap_progress_total 4191
telemt_me_writer_removed_unexpected_total 69
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 306
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 3942
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 322
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 3865
telemt_me_writer_teardown_success_total{mode="normal"} 4248
telemt_me_writer_teardown_noop_total 4192
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 8138
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 8315
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 8369
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 8414
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 8438
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 8440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 8440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 8440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 8440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 8440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 8440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 8440
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 8440
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 2.651187
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 8440
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 22
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 65
telemt_me_writer_removed_unexpected_minus_restored_total 4
telemt_user_connections_total{user="hello"} 144327
telemt_user_connections_current{user="hello"} 618
telemt_user_octets_from_client{user="hello"} 1680713148 (1.57 GB)
telemt_user_octets_to_client{user="hello"} 50426252872 (46.96 GB)
telemt_user_unique_ips_current{user="hello"} 299
telemt_user_unique_ips_recent_window{user="hello"} 71
```

## psb.hosting №1

```
telemt 3.3.28

telemt_uptime_seconds 24880.5 (6h 54m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 687538
telemt_connections_bad_total 39627
telemt_connections_current 490
telemt_connections_me_current 490
telemt_handshake_timeouts_total 26027
telemt_upstream_connect_attempt_total 10676
telemt_upstream_connect_success_total 10489
telemt_upstream_connect_fail_total 169
telemt_upstream_connect_attempts_per_request{bucket="1"} 10658
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 4721
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 5733
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 35
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 169
telemt_me_reconnect_attempts_total 926
telemt_me_reconnect_success_total 322
telemt_me_reader_eof_total 276
telemt_me_idle_close_by_peer_total 276
telemt_me_route_drop_no_conn_total 328521
telemt_me_route_drop_channel_closed_total 1
telemt_me_route_drop_queue_full_total 1
telemt_me_route_drop_queue_full_profile_total{profile="high"} 1
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 555389
telemt_me_endpoint_quarantine_total 225
telemt_me_single_endpoint_outage_enter_total 14
telemt_me_single_endpoint_outage_exit_total 14
telemt_me_single_endpoint_outage_reconnect_attempt_total 14
telemt_me_single_endpoint_outage_reconnect_success_total 14
telemt_me_single_endpoint_quarantine_bypass_total 14
telemt_me_single_endpoint_shadow_rotate_total 202
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 16
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
telemt_me_writers_active_current 43
telemt_desync_total 2424
telemt_desync_full_logged_total 1393
telemt_desync_suppressed_total 1031
telemt_desync_frames_bucket_total{bucket="1_2"} 517
telemt_desync_frames_bucket_total{bucket="3_10"} 908
telemt_desync_frames_bucket_total{bucket="gt_10"} 999
telemt_pool_swap_total 27
telemt_pool_force_close_total 748
telemt_me_writer_close_signal_drop_total 57
telemt_me_draining_writers_reap_progress_total 9422
telemt_me_writer_removed_unexpected_total 259
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 824
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 8861
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 741
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 7
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 8674
telemt_me_writer_teardown_success_total{mode="normal"} 9685
telemt_me_writer_teardown_noop_total 9422
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 18646
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 18915
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 19001
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 19093
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 19105
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 19107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 19107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 19107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 19107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 19107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 19107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 19107
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 19107
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.386965
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 19107
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 57
telemt_me_refill_failed_total 32
telemt_me_writer_restored_same_endpoint_total 221
telemt_me_writer_restored_fallback_total 9
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 29
telemt_user_connections_total{user="hello"} 554598
telemt_user_connections_current{user="hello"} 490
telemt_user_octets_from_client{user="hello"} 9250734060 (8.62 GB)
telemt_user_octets_to_client{user="hello"} 194062024984 (180.73 GB)
telemt_user_unique_ips_current{user="hello"} 324
telemt_user_unique_ips_recent_window{user="hello"} 120
```

## psb.hosting №2

```
telemt 3.3.28

telemt_uptime_seconds 99740.5 (27h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7481914
telemt_connections_bad_total 596390
telemt_connections_current 1550
telemt_connections_me_current 1550
telemt_handshake_timeouts_total 243471
telemt_upstream_connect_attempt_total 36220
telemt_upstream_connect_success_total 36150
telemt_upstream_connect_fail_total 7
telemt_upstream_connect_attempts_per_request{bucket="1"} 36157
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 16367
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19619
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 6
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 158
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 7
telemt_me_keepalive_timeout_total 157
telemt_me_reconnect_attempts_total 1497
telemt_me_reconnect_success_total 749
telemt_me_reader_eof_total 758
telemt_me_idle_close_by_peer_total 758
telemt_me_route_drop_no_conn_total 4504145
telemt_me_route_drop_channel_closed_total 66
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 6097390
telemt_me_endpoint_quarantine_total 630
telemt_me_single_endpoint_outage_enter_total 5
telemt_me_single_endpoint_outage_exit_total 5
telemt_me_single_endpoint_outage_reconnect_attempt_total 5
telemt_me_single_endpoint_outage_reconnect_success_total 5
telemt_me_single_endpoint_quarantine_bypass_total 5
telemt_me_single_endpoint_shadow_rotate_total 740
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 24
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
telemt_desync_total 25857
telemt_desync_full_logged_total 8553
telemt_desync_suppressed_total 17304
telemt_desync_frames_bucket_total{bucket="1_2"} 5561
telemt_desync_frames_bucket_total{bucket="3_10"} 10087
telemt_desync_frames_bucket_total{bucket="gt_10"} 10209
telemt_pool_swap_total 107
telemt_pool_force_close_total 3608
telemt_pool_stale_pick_total 17
telemt_me_writer_close_signal_drop_total 576
telemt_me_draining_writers_reap_progress_total 33018
telemt_me_writer_removed_unexpected_total 729
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2788
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30517
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 40
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3369
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 239
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29410
telemt_me_writer_teardown_success_total{mode="normal"} 33305
telemt_me_writer_teardown_noop_total 33062
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60456
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62227
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 63171
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 64581
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 65529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66066
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66356
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66367
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66367
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 153.642946
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66367
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 576
telemt_me_refill_failed_total 39
telemt_me_writer_restored_same_endpoint_total 669
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 8
telemt_me_writer_removed_unexpected_minus_restored_total 55
telemt_user_connections_total{user="hello"} 6089755
telemt_user_connections_current{user="hello"} 1550
telemt_user_octets_from_client{user="hello"} 104322353864 (97.16 GB)
telemt_user_octets_to_client{user="hello"} 2006459224008 (1.82 TB)
telemt_user_unique_ips_current{user="hello"} 767
telemt_user_unique_ips_recent_window{user="hello"} 159
```

## koara.io №1

```
telemt 3.3.28

telemt_uptime_seconds 99741.8 (27h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6156589
telemt_connections_bad_total 579803
telemt_connections_current 1736
telemt_connections_me_current 1736
telemt_relay_adaptive_promotions_total 16
telemt_relay_adaptive_hard_promotions_total 14
telemt_handshake_timeouts_total 203147
telemt_upstream_connect_attempt_total 40285
telemt_upstream_connect_success_total 39905
telemt_upstream_connect_fail_total 184
telemt_upstream_connect_attempts_per_request{bucket="1"} 40089
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 19970
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19347
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 33
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 555
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 184
telemt_me_keepalive_failed_total 1
telemt_me_keepalive_timeout_total 116
telemt_me_reconnect_attempts_total 1847
telemt_me_reconnect_success_total 810
telemt_me_reader_eof_total 786
telemt_me_idle_close_by_peer_total 786
telemt_me_route_drop_no_conn_total 2194416
telemt_me_route_drop_channel_closed_total 255
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4614867
telemt_me_endpoint_quarantine_total 606
telemt_me_single_endpoint_outage_enter_total 7
telemt_me_single_endpoint_outage_exit_total 7
telemt_me_single_endpoint_outage_reconnect_attempt_total 7
telemt_me_single_endpoint_outage_reconnect_success_total 7
telemt_me_single_endpoint_quarantine_bypass_total 7
telemt_me_single_endpoint_shadow_rotate_total 762
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 22144
telemt_desync_full_logged_total 7496
telemt_desync_suppressed_total 14648
telemt_desync_frames_bucket_total{bucket="1_2"} 5332
telemt_desync_frames_bucket_total{bucket="3_10"} 8590
telemt_desync_frames_bucket_total{bucket="gt_10"} 8222
telemt_pool_swap_total 108
telemt_pool_force_close_total 3246
telemt_pool_stale_pick_total 4
telemt_me_writer_close_signal_drop_total 346
telemt_me_draining_writers_reap_progress_total 31576
telemt_me_writer_removed_unexpected_total 765
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2705
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 29571
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 6
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 3047
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 199
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 28330
telemt_me_writer_teardown_success_total{mode="normal"} 32276
telemt_me_writer_teardown_noop_total 31582
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 60599
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 62104
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 62672
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 63242
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63653
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63838
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63858
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63858
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 48.002972
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63858
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 346
telemt_me_refill_failed_total 55
telemt_me_writer_restored_same_endpoint_total 706
telemt_me_writer_restored_fallback_total 8
telemt_me_async_recovery_trigger_total 20
telemt_me_writer_removed_unexpected_minus_restored_total 51
telemt_user_connections_total{user="hello"} 4552009
telemt_user_connections_current{user="hello"} 1736
telemt_user_octets_from_client{user="hello"} 138316188245 (128.82 GB)
telemt_user_octets_to_client{user="hello"} 2132057932239 (1.94 TB)
telemt_user_msgs_from_client{user="hello"} 39229
telemt_user_msgs_to_client{user="hello"} 49019
telemt_user_unique_ips_current{user="hello"} 843
telemt_user_unique_ips_recent_window{user="hello"} 123
```

## koara.io №2

```
telemt 3.3.28

telemt_uptime_seconds 99705.9 (27h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6064635
telemt_connections_bad_total 540565
telemt_connections_current 1238
telemt_connections_me_current 1238
telemt_relay_adaptive_promotions_total 6
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 194280
telemt_upstream_connect_attempt_total 46639
telemt_upstream_connect_success_total 46327
telemt_upstream_connect_fail_total 135
telemt_upstream_connect_attempts_per_request{bucket="1"} 46462
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 24133
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20781
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 366
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 1047
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 135
telemt_me_keepalive_timeout_total 58
telemt_me_reconnect_attempts_total 1822
telemt_me_reconnect_success_total 835
telemt_me_reader_eof_total 781
telemt_me_idle_close_by_peer_total 781
telemt_me_route_drop_no_conn_total 2109719
telemt_me_route_drop_channel_closed_total 109
telemt_me_route_drop_queue_full_total 5
telemt_me_route_drop_queue_full_profile_total{profile="high"} 5
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4527346
telemt_me_endpoint_quarantine_total 674
telemt_me_single_endpoint_outage_enter_total 9
telemt_me_single_endpoint_outage_exit_total 9
telemt_me_single_endpoint_outage_reconnect_attempt_total 9
telemt_me_single_endpoint_outage_reconnect_success_total 6
telemt_me_single_endpoint_quarantine_bypass_total 9
telemt_me_single_endpoint_shadow_rotate_total 746
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
telemt_me_writers_active_current 45
telemt_desync_total 21991
telemt_desync_full_logged_total 7337
telemt_desync_suppressed_total 14654
telemt_desync_frames_bucket_total{bucket="1_2"} 5378
telemt_desync_frames_bucket_total{bucket="3_10"} 8419
telemt_desync_frames_bucket_total{bucket="gt_10"} 8194
telemt_pool_swap_total 107
telemt_pool_force_close_total 3150
telemt_pool_stale_pick_total 1618
telemt_me_writer_close_signal_drop_total 369
telemt_me_draining_writers_reap_progress_total 33052
telemt_me_writer_removed_unexpected_total 747
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2761
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 31047
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 11
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2935
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 215
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 29902
telemt_me_writer_teardown_success_total{mode="normal"} 33808
telemt_me_writer_teardown_noop_total 33063
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 64386
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 65734
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 66164
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 66621
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 66828
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 66853
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 66871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 66871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 66871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 66871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 66871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 66871
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 66871
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 25.538110
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 66871
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 369
telemt_me_refill_failed_total 54
telemt_me_writer_restored_same_endpoint_total 723
telemt_me_writer_restored_fallback_total 4
telemt_me_no_writer_failfast_total 4
telemt_me_async_recovery_trigger_total 42
telemt_me_writer_removed_unexpected_minus_restored_total 20
telemt_user_connections_total{user="hello"} 4528305
telemt_user_connections_current{user="hello"} 1238
telemt_user_octets_from_client{user="hello"} 131927058679 (122.87 GB)
telemt_user_octets_to_client{user="hello"} 2075876741403 (1.89 TB)
telemt_user_msgs_from_client{user="hello"} 44246
telemt_user_msgs_to_client{user="hello"} 113178
telemt_user_unique_ips_current{user="hello"} 635
telemt_user_unique_ips_recent_window{user="hello"} 143
```

## landvps.ru

```
telemt 3.3.28

telemt_uptime_seconds 99745.3 (27h 42m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 20035211
telemt_connections_bad_total 1493715
telemt_connections_current 2338
telemt_connections_me_current 2338
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 580357
telemt_upstream_connect_attempt_total 189695
telemt_upstream_connect_success_total 172043
telemt_upstream_connect_fail_total 16038
telemt_upstream_connect_attempts_per_request{bucket="1"} 188081
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 121618
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 40319
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1221
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 8885
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 16038
telemt_me_keepalive_timeout_total 398
telemt_me_reconnect_attempts_total 64366
telemt_me_reconnect_success_total 2170
telemt_me_reader_eof_total 1357
telemt_me_idle_close_by_peer_total 1356
telemt_me_route_drop_no_conn_total 39459052
telemt_me_route_drop_channel_closed_total 122
telemt_me_route_drop_queue_full_total 12
telemt_me_route_drop_queue_full_profile_total{profile="high"} 12
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 16293004
telemt_me_writer_pick_total{mode="p2c",result="full"} 5
telemt_me_writer_pick_total{mode="p2c",result="closed"} 5
telemt_me_endpoint_quarantine_total 766
telemt_me_single_endpoint_outage_enter_total 123
telemt_me_single_endpoint_outage_exit_total 123
telemt_me_single_endpoint_outage_reconnect_attempt_total 259
telemt_me_single_endpoint_outage_reconnect_success_total 62
telemt_me_single_endpoint_quarantine_bypass_total 259
telemt_me_single_endpoint_shadow_rotate_total 777
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 56
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
telemt_desync_total 31360
telemt_desync_full_logged_total 9341
telemt_desync_suppressed_total 22019
telemt_desync_frames_bucket_total{bucket="1_2"} 6831
telemt_desync_frames_bucket_total{bucket="3_10"} 13887
telemt_desync_frames_bucket_total{bucket="gt_10"} 10642
telemt_pool_swap_total 102
telemt_pool_force_close_total 3377
telemt_pool_stale_pick_total 29
telemt_me_writer_close_signal_drop_total 762
telemt_me_draining_writers_reap_progress_total 30989
telemt_me_writer_removed_unexpected_total 2016
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 4234
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 28507
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 23
telemt_me_writer_teardown_attempt_total{reason="close_rpc_channel_closed",mode="normal"} 3
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2861
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 516
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 27612
telemt_me_writer_teardown_success_total{mode="normal"} 32741
telemt_me_writer_teardown_noop_total 31015
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 57212
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 59553
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 60802
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 62392
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 63320
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 63655
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 63737
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 63739
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 63742
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 63747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 63747
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 63751
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 63756
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 212.164034
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 63756
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 762
telemt_me_refill_failed_total 3789
telemt_me_writer_restored_same_endpoint_total 1503
telemt_me_writer_restored_fallback_total 21
telemt_me_no_writer_failfast_total 666
telemt_me_async_recovery_trigger_total 14678
telemt_me_writer_removed_unexpected_minus_restored_total 492
telemt_user_connections_total{user="hello"} 16420818
telemt_user_connections_current{user="hello"} 2338
telemt_user_octets_from_client{user="hello"} 190496953636 (177.41 GB)
telemt_user_octets_to_client{user="hello"} 1130904761902 (1.03 TB)
telemt_user_msgs_from_client{user="hello"} 367794
telemt_user_msgs_to_client{user="hello"} 650852
telemt_user_unique_ips_current{user="hello"} 1042
telemt_user_unique_ips_recent_window{user="hello"} 221
```

## rdp-onedash.ru №1

```
telemt 3.3.28

telemt_uptime_seconds 99712.7 (27h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 5856041
telemt_connections_bad_total 552349
telemt_connections_current 1550
telemt_connections_me_current 1550
telemt_relay_adaptive_promotions_total 5
telemt_relay_adaptive_hard_promotions_total 5
telemt_handshake_timeouts_total 121015
telemt_upstream_connect_attempt_total 54793
telemt_upstream_connect_success_total 54168
telemt_upstream_connect_fail_total 534
telemt_upstream_connect_attempts_per_request{bucket="1"} 54702
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 32156
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 21670
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 341
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 534
telemt_me_reconnect_attempts_total 68114
telemt_me_reconnect_success_total 1696
telemt_me_reader_eof_total 1474
telemt_me_idle_close_by_peer_total 1473
telemt_me_route_drop_no_conn_total 2361808
telemt_me_route_drop_channel_closed_total 10
telemt_me_route_drop_queue_full_total 39
telemt_me_route_drop_queue_full_profile_total{profile="high"} 39
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4564656
telemt_me_endpoint_quarantine_total 663
telemt_me_single_endpoint_outage_enter_total 20
telemt_me_single_endpoint_outage_exit_total 20
telemt_me_single_endpoint_outage_reconnect_attempt_total 21
telemt_me_single_endpoint_outage_reconnect_success_total 20
telemt_me_single_endpoint_quarantine_bypass_total 21
telemt_me_single_endpoint_shadow_rotate_total 747
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
telemt_desync_total 23021
telemt_desync_full_logged_total 8070
telemt_desync_suppressed_total 14951
telemt_desync_frames_bucket_total{bucket="1_2"} 4364
telemt_desync_frames_bucket_total{bucket="3_10"} 8917
telemt_desync_frames_bucket_total{bucket="gt_10"} 9740
telemt_pool_swap_total 102
telemt_pool_force_close_total 2996
telemt_pool_stale_pick_total 54
telemt_me_writer_close_signal_drop_total 379
telemt_me_draining_writers_reap_progress_total 34445
telemt_me_writer_removed_unexpected_total 1519
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3651
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32337
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 1
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2595
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 401
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31449
telemt_me_writer_teardown_success_total{mode="normal"} 35988
telemt_me_writer_teardown_noop_total 34446
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 69205
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 70009
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 70282
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 70402
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 70431
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 70434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 70434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 70434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 70434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 70434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 70434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 70434
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 70434
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 7.971966
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 70434
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 379
telemt_me_refill_failed_total 4119
telemt_me_writer_restored_same_endpoint_total 1431
telemt_me_writer_restored_fallback_total 30
telemt_me_no_writer_failfast_total 223
telemt_me_async_recovery_trigger_total 7257
telemt_me_writer_removed_unexpected_minus_restored_total 58
telemt_user_connections_total{user="hello"} 4557752
telemt_user_connections_current{user="hello"} 1550
telemt_user_octets_from_client{user="hello"} 122352329788 (113.95 GB)
telemt_user_octets_to_client{user="hello"} 1863756445054 (1.70 TB)
telemt_user_msgs_from_client{user="hello"} 77823
telemt_user_msgs_to_client{user="hello"} 338392
telemt_user_unique_ips_current{user="hello"} 780
telemt_user_unique_ips_recent_window{user="hello"} 124
```

## rdp-onedash.ru №2

```
telemt 3.3.28

telemt_uptime_seconds 36548.5 (10h 9m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 3726233
telemt_connections_bad_total 131963
telemt_connections_current 1132
telemt_connections_me_current 1132
telemt_relay_adaptive_promotions_total 4
telemt_relay_adaptive_hard_promotions_total 3
telemt_handshake_timeouts_total 1545760
telemt_upstream_connect_attempt_total 23097
telemt_upstream_connect_success_total 22950
telemt_upstream_connect_fail_total 140
telemt_upstream_connect_attempts_per_request{bucket="1"} 23090
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 15230
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 7654
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 66
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 140
telemt_me_reconnect_attempts_total 45597
telemt_me_reconnect_success_total 895
telemt_me_reader_eof_total 567
telemt_me_idle_close_by_peer_total 567
telemt_me_route_drop_no_conn_total 999135
telemt_me_route_drop_channel_closed_total 4
telemt_me_route_drop_queue_full_total 2
telemt_me_route_drop_queue_full_profile_total{profile="high"} 2
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 1806422
telemt_me_endpoint_quarantine_total 263
telemt_me_single_endpoint_outage_enter_total 10
telemt_me_single_endpoint_outage_exit_total 10
telemt_me_single_endpoint_outage_reconnect_attempt_total 49
telemt_me_single_endpoint_outage_reconnect_success_total 10
telemt_me_single_endpoint_quarantine_bypass_total 49
telemt_me_single_endpoint_shadow_rotate_total 277
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
telemt_me_writers_active_current 44
telemt_me_floor_cap_block_total 23
telemt_me_floor_swap_idle_failed_total 23
telemt_desync_total 10007
telemt_desync_full_logged_total 3433
telemt_desync_suppressed_total 6574
telemt_desync_frames_bucket_total{bucket="1_2"} 1765
telemt_desync_frames_bucket_total{bucket="3_10"} 3835
telemt_desync_frames_bucket_total{bucket="gt_10"} 4407
telemt_pool_swap_total 39
telemt_pool_force_close_total 1273
telemt_pool_stale_pick_total 15
telemt_me_writer_close_signal_drop_total 121
telemt_me_draining_writers_reap_progress_total 12537
telemt_me_writer_removed_unexpected_total 647
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 1321
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 11883
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 1067
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 206
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 11264
telemt_me_writer_teardown_success_total{mode="normal"} 13204
telemt_me_writer_teardown_noop_total 12539
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 25285
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 25549
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 25637
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 25743
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 25743
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 3.093592
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 25743
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 121
telemt_me_refill_failed_total 2597
telemt_me_writer_restored_same_endpoint_total 803
telemt_me_writer_restored_fallback_total 11
telemt_me_no_writer_failfast_total 287
telemt_me_async_recovery_trigger_total 4264
telemt_user_connections_total{user="hello"} 1810169
telemt_user_connections_current{user="hello"} 1132
telemt_user_octets_from_client{user="hello"} 52758754764 (49.14 GB)
telemt_user_octets_to_client{user="hello"} 774112377406 (720.95 GB)
telemt_user_msgs_from_client{user="hello"} 65124
telemt_user_msgs_to_client{user="hello"} 212950
telemt_user_unique_ips_current{user="hello"} 614
telemt_user_unique_ips_recent_window{user="hello"} 116
```

## hostvds.com

```
telemt 3.3.28

telemt_uptime_seconds 17519.7 (4h 51m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 164048
telemt_connections_bad_total 1399
telemt_connections_current 342
telemt_connections_me_current 342
telemt_handshake_timeouts_total 4030
telemt_upstream_connect_attempt_total 8083
telemt_upstream_connect_success_total 8063
telemt_upstream_connect_fail_total 19
telemt_upstream_connect_attempts_per_request{bucket="1"} 8082
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 3474
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 4520
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 69
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 19
telemt_me_reconnect_attempts_total 168
telemt_me_reconnect_success_total 106
telemt_me_reader_eof_total 106
telemt_me_idle_close_by_peer_total 106
telemt_me_route_drop_no_conn_total 46328
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 144310
telemt_me_endpoint_quarantine_total 161
telemt_me_single_endpoint_shadow_rotate_total 156
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 3
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
telemt_me_writers_active_current 43
telemt_desync_total 973
telemt_desync_full_logged_total 242
telemt_desync_suppressed_total 731
telemt_desync_frames_bucket_total{bucket="1_2"} 384
telemt_desync_frames_bucket_total{bucket="3_10"} 351
telemt_desync_frames_bucket_total{bucket="gt_10"} 238
telemt_pool_swap_total 19
telemt_pool_force_close_total 442
telemt_me_writer_close_signal_drop_total 20
telemt_me_draining_writers_reap_progress_total 7247
telemt_me_writer_removed_unexpected_total 104
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 477
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 6876
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 440
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 6805
telemt_me_writer_teardown_success_total{mode="normal"} 7353
telemt_me_writer_teardown_noop_total 7247
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 14450
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 14572
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 14590
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 14600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 14600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 14600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 14600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 14600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 14600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 14600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 14600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 14600
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 14600
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 0.807196
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 14600
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 20
telemt_me_refill_failed_total 4
telemt_me_writer_restored_same_endpoint_total 98
telemt_me_writer_removed_unexpected_minus_restored_total 6
telemt_user_connections_total{user="hello"} 144030
telemt_user_connections_current{user="hello"} 342
telemt_user_octets_from_client{user="hello"} 2682657928 (2.50 GB)
telemt_user_octets_to_client{user="hello"} 84152722224 (78.37 GB)
telemt_user_unique_ips_current{user="hello"} 144
telemt_user_unique_ips_recent_window{user="hello"} 40
```

## 4vps.su №1

```
telemt 3.3.28

telemt_uptime_seconds 99717.1 (27h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 7070184
telemt_connections_bad_total 716598
telemt_connections_current 1755
telemt_connections_me_current 1755
telemt_handshake_timeouts_total 201219
telemt_upstream_connect_attempt_total 38260
telemt_upstream_connect_success_total 38113
telemt_upstream_connect_fail_total 110
telemt_upstream_connect_attempts_per_request{bucket="1"} 38223
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 18923
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 19149
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 1
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 40
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 110
telemt_me_reconnect_attempts_total 1503
telemt_me_reconnect_success_total 789
telemt_me_reader_eof_total 769
telemt_me_idle_close_by_peer_total 769
telemt_me_route_drop_no_conn_total 2100656
telemt_me_route_drop_channel_closed_total 52
telemt_me_route_drop_queue_full_total 23
telemt_me_route_drop_queue_full_profile_total{profile="high"} 23
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 5330786
telemt_me_endpoint_quarantine_total 685
telemt_me_single_endpoint_outage_enter_total 8
telemt_me_single_endpoint_outage_exit_total 8
telemt_me_single_endpoint_outage_reconnect_attempt_total 8
telemt_me_single_endpoint_outage_reconnect_success_total 8
telemt_me_single_endpoint_quarantine_bypass_total 8
telemt_me_single_endpoint_shadow_rotate_total 764
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 29
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
telemt_desync_total 20594
telemt_desync_full_logged_total 6876
telemt_desync_suppressed_total 13718
telemt_desync_frames_bucket_total{bucket="1_2"} 5016
telemt_desync_frames_bucket_total{bucket="3_10"} 7468
telemt_desync_frames_bucket_total{bucket="gt_10"} 8110
telemt_pool_swap_total 110
telemt_pool_force_close_total 2996
telemt_pool_stale_pick_total 3
telemt_me_writer_close_signal_drop_total 372
telemt_me_draining_writers_reap_progress_total 34428
telemt_me_writer_removed_unexpected_total 742
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 2774
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 32413
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 2
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2908
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 88
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 31432
telemt_me_writer_teardown_success_total{mode="normal"} 35187
telemt_me_writer_teardown_noop_total 34430
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 68272
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 69151
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 69329
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 69529
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 69617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 69617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 69617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 69617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 69617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 69617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 69617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 69617
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 69617
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.571383
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 69617
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 372
telemt_me_refill_failed_total 37
telemt_me_writer_restored_same_endpoint_total 704
telemt_me_writer_restored_fallback_total 5
telemt_me_async_recovery_trigger_total 14
telemt_me_writer_removed_unexpected_minus_restored_total 33
telemt_user_connections_total{user="hello"} 5305968
telemt_user_connections_current{user="hello"} 1755
telemt_user_octets_from_client{user="hello"} 107883261440 (100.47 GB)
telemt_user_octets_to_client{user="hello"} 2492157096416 (2.27 TB)
telemt_user_unique_ips_current{user="hello"} 784
telemt_user_unique_ips_recent_window{user="hello"} 146
```

## 4vps.su №2

```
telemt 3.3.28

telemt_uptime_seconds 99713.7 (27h 41m)
telemt_telemetry_core_enabled 1
telemt_telemetry_user_enabled 1
telemt_telemetry_me_level{level="normal"} 1
telemt_connections_total 6057243
telemt_connections_bad_total 595634
telemt_connections_current 1574
telemt_connections_me_current 1574
telemt_relay_adaptive_promotions_total 14
telemt_relay_adaptive_hard_promotions_total 12
telemt_handshake_timeouts_total 168096
telemt_upstream_connect_attempt_total 54185
telemt_upstream_connect_success_total 53774
telemt_upstream_connect_fail_total 352
telemt_upstream_connect_attempts_per_request{bucket="1"} 54126
telemt_upstream_connect_duration_success_total{bucket="le_100ms"} 31754
telemt_upstream_connect_duration_success_total{bucket="101_500ms"} 20887
telemt_upstream_connect_duration_success_total{bucket="501_1000ms"} 518
telemt_upstream_connect_duration_success_total{bucket="gt_1000ms"} 615
telemt_upstream_connect_duration_fail_total{bucket="gt_1000ms"} 352
telemt_me_reconnect_attempts_total 5389
telemt_me_reconnect_success_total 1098
telemt_me_reader_eof_total 980
telemt_me_idle_close_by_peer_total 980
telemt_me_seq_mismatch_total 42
telemt_me_route_drop_no_conn_total 2154563
telemt_me_route_drop_channel_closed_total 189
telemt_me_route_drop_queue_full_total 11
telemt_me_route_drop_queue_full_profile_total{profile="high"} 11
telemt_me_writer_pick_total{mode="p2c",result="success_try"} 4701537
telemt_me_endpoint_quarantine_total 790
telemt_me_single_endpoint_outage_enter_total 27
telemt_me_single_endpoint_outage_exit_total 27
telemt_me_single_endpoint_outage_reconnect_attempt_total 27
telemt_me_single_endpoint_outage_reconnect_success_total 25
telemt_me_single_endpoint_quarantine_bypass_total 27
telemt_me_single_endpoint_shadow_rotate_total 759
telemt_me_single_endpoint_shadow_rotate_skipped_quarantine_total 31
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
telemt_me_writers_active_current 43
telemt_desync_total 19369
telemt_desync_full_logged_total 6507
telemt_desync_suppressed_total 12862
telemt_desync_frames_bucket_total{bucket="1_2"} 4873
telemt_desync_frames_bucket_total{bucket="3_10"} 7047
telemt_desync_frames_bucket_total{bucket="gt_10"} 7449
telemt_pool_swap_total 108
telemt_pool_force_close_total 2954
telemt_pool_stale_pick_total 358
telemt_me_writer_close_signal_drop_total 367
telemt_me_draining_writers_reap_progress_total 33139
telemt_me_writer_removed_unexpected_total 992
telemt_me_writer_teardown_attempt_total{reason="reader_exit",mode="normal"} 3259
telemt_me_writer_teardown_attempt_total{reason="writer_task_exit",mode="normal"} 30917
telemt_me_writer_teardown_attempt_total{reason="route_channel_closed",mode="normal"} 4
telemt_me_writer_teardown_attempt_total{reason="reap_timeout_expired",mode="normal"} 2731
telemt_me_writer_teardown_attempt_total{reason="reap_threshold_force",mode="normal"} 223
telemt_me_writer_teardown_attempt_total{reason="reap_empty",mode="normal"} 30185
telemt_me_writer_teardown_success_total{mode="normal"} 34176
telemt_me_writer_teardown_noop_total 33143
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.001"} 65711
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.005"} 66745
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.01"} 67086
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.025"} 67281
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.05"} 67319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.1"} 67319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.25"} 67319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="0.5"} 67319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="1"} 67319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="2.5"} 67319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="5"} 67319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="10"} 67319
telemt_me_writer_teardown_duration_seconds_bucket{mode="normal",le="+Inf"} 67319
telemt_me_writer_teardown_duration_seconds_sum{mode="normal"} 10.903072
telemt_me_writer_teardown_duration_seconds_count{mode="normal"} 67319
telemt_me_writer_cleanup_side_effect_failures_total{step="close_signal_channel_closed"} 367
telemt_me_refill_failed_total 248
telemt_me_writer_restored_same_endpoint_total 853
telemt_me_writer_restored_fallback_total 55
telemt_me_no_writer_failfast_total 1
telemt_me_async_recovery_trigger_total 76
telemt_me_writer_removed_unexpected_minus_restored_total 84
telemt_user_connections_total{user="hello"} 4704786
telemt_user_connections_current{user="hello"} 1574
telemt_user_octets_from_client{user="hello"} 88948416357 (82.84 GB)
telemt_user_octets_to_client{user="hello"} 2017522036228 (1.83 TB)
telemt_user_msgs_from_client{user="hello"} 75721
telemt_user_msgs_to_client{user="hello"} 209236
telemt_user_unique_ips_current{user="hello"} 735
telemt_user_unique_ips_recent_window{user="hello"} 151
```